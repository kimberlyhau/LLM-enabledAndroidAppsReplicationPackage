# LLM-enabledAndroidApps Replication Package

## App_Characteristics_MasterSheet.xlsx

This spreadsheet lists every app in the dataset, along with their LLM integration strategy and data characteristics. Data characteristics included are commit lifetime (number of days between the first and last commit), average days per commit, llm_commits (the number of commits that included a change to an LLM-related file), llm_tags (the number of tags preceeded by an LLM-related commit), llm_tags_percentage (the percentage of llm_tags/total number of tags), llm_releases (the number of releases preceeded by an LLM-related commit), llm_releases_percentage, loc (total lines of code). Additionally, data characteristics provided by the Github API such as number of stars, issues, tags, contributors, created_at (the date the repository was first created), pushed_at (the date of the last commit, as of December 1, 2024), updated_at (the date of the last update to the repository).

## App_Descriptions_and_Assigned_Functionality.xlsx

This spreadsheet lists the repository description (if available) of each app in the dataset, and their corresponding assigned main functionality. We manually assign functionalities to apps without a repository description by carefully looking into their readme files. 

## Commit_Messages_and_Assigned_Topics.xlsx

This spreadsheet lists the commit messages associated with each LLM-related commit for each app, and their corresponding assigned commit topic.
