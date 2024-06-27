# Merge PRs GitHub Action

<!--Start Count Merged PRs-->
  <span><img src="https://img.shields.io/badge/Total_Merged_PRs-33-1877F2?style=for-the-badge"></span>
<!--Finish Count Merged PRs-->

<!--Start Merged PRs-->
1. 🥳 Merged PR on [11](https://github.com/monacodelisa/LGBTQ-definitions/pull/11) - [monacodelisa/LGBTQ-definitions](https://github.com/monacodelisa/LGBTQ-definitions)
2. 🎉 Merged PR on [876](https://github.com/glasskube/glasskube/pull/876) - [glasskube/glasskube](https://github.com/glasskube/glasskube)
3. 🎊 Merged PR on [7](https://github.com/monacodelisa/LGBTQ-definitions/pull/7) - [monacodelisa/LGBTQ-definitions](https://github.com/monacodelisa/LGBTQ-definitions)
4. 🥂 Merged PR on [5](https://github.com/monacodelisa/LGBTQ-definitions/pull/5) - [monacodelisa/LGBTQ-definitions](https://github.com/monacodelisa/LGBTQ-definitions)
5. 🙌🏼 Merged PR on [50](https://github.com/pinacai/PINAC_Workspace/pull/50) - [pinacai/PINAC_Workspace](https://github.com/pinacai/PINAC_Workspace)
<!--Finish Merged PRs-->

## Step-by-Step Guide to Set Up GitHub Action for Merging PRs 

### How to Use? 

1. Go to your Profile `README` Repository and create the `.github/workflows/action.yml` file with the provided configuration.
2. Add main.py in your Profile `README` Repository, and replace your username with ```ParthJohri```

   ```
   url = "https://api.github.com/search/issues?q=is:pr+author:ParthJohri+is:merged"
   ```
   
4. Ensure your Profile `README.md` contains the below comments, to show your merged PRs in your Profile ReadME:
```
   <!--Start Count Merged PRs-->

   <!--Finish Count Merged PRs-->
   
   <!--Start Merged PRs-->
   
   <!--Finish Merged PRs-->
```
4. By default the corn jobs runs every 6 hours or you can also manually start it. You can also make use of [Cron Tab](https://crontab.guru/) to change the cron job time as per your requirement.


## Contributing to This Project

Thank you for your interest in contributing to this project! Here are some guidelines to help you get started:


1. Fork the repository on GitHub.
2. Clone your fork to your local machine:
   ```
   git clone https://github.com/your-username/Merge-PRs-GitHub-Action.git
   ```
3. Create a new branch for your feature or bugfix:
   ```
   git checkout -b my-feature-branch
   ```
4. Make your changes and commit them with a descriptive message:
   ```
   git commit -m "Description of your changes"
   ```
5. Push your branch to GitHub:
   ```
   git push origin my-feature-branch
   ```

### Submitting Your Changes

1. Go to the repository on GitHub and create a pull request.
2. Describe your changes and what they do.
