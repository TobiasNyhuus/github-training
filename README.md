# GitHub training for the Nordic Accessibility Community Group

Practise making a small text change and proposing it through a pull request. This repository is a practice space for the session on **27 October 2026, 14:30–15:15 Copenhagen time (CET)**. You can also use it afterwards.

The files contain deliberate spelling mistakes. Your task is to fix one, check your change, and ask for it to be reviewed. You can do everything on the GitHub website.

## Git and GitHub in plain language

Git records changes to files so earlier versions can be compared. GitHub hosts those files online and adds ways to discuss and propose changes. A repository is a project’s files and their history. Here we work with ordinary text, so no coding knowledge or installation is needed.

This practice hub belongs to **TobiasNyhuus**. It is a fork of the organisation’s original training repository. For this session, send your pull request to **TobiasNyhuus/github-training**, branch **main**.

## Before you start

- Sign in to your GitHub account. If you need an account, [sign up for GitHub](https://github.com/signup) before the session.
- Keep these instructions available while you work in another tab.
- Your fork, pull request, and any comments in this public repository will be public. Use the sample text; no personal details are needed.

## Make your practice pull request

1. At the top of this repository, select **Fork**, then **Create a new fork** if that menu appears. Choose your personal account as the owner, keep the name `github-training`, and select **Create fork**. A fork is your own copy on GitHub. If you already have a fork, open that copy instead.
2. Check that the repository name at the top is **your username / github-training**. Open the branch selector, initially **main**. Type `fix-contribution-spelling` and select **Create branch: fix-contribution-spelling from main**. A branch keeps this proposed edit separate from the starting version.
3. In your own fork’s file list on that branch, open `practice.md`. Select **Edit this file** (the pencil button). Change `contributon` to `contribution`. Leave the other text unchanged for now.
4. Select **Preview** and read the corrected sentence. If needed, return to **Edit** to adjust it.
5. Select **Commit changes…**. Replace any prefilled commit message with `Correct contribution spelling`. Keep the commit on your `fix-contribution-spelling` branch, then select **Commit changes**. A commit records your edit with a short explanation.
6. Return to your fork's file list using the **github-training** breadcrumb above the file. Check that `fix-contribution-spelling` is still selected. Use **Contribute → Open pull request**, or **Compare & pull request** if GitHub offers that banner. A pull request proposes your saved edit to a chosen destination.
7. Check the comparison before continuing. GitHub may initially select the organisation’s upstream repository; change the base repository to **TobiasNyhuus/github-training**. **Base** is where you propose the change; **head** is where your edit lives:
   - **Base repository:** `TobiasNyhuus/github-training`
   - **Base:** `main`
   - **Head repository:** your personal `github-training` fork
   - **Compare:** `fix-contribution-spelling`
8. Read the file comparison. It should contain only your one-word correction in `practice.md`. Removed and added lines are marked with minus and plus signs. If there are unrelated changes, stop and check the selected repositories and branches.
9. If the title and description fields are not yet visible, select **Create pull request** to open them. Replace the title with `[Practice] Correct contribution spelling`. Explain what you changed and why. You may use this example as a starting point:

   ```markdown
   ## Problem

   The practice sentence contains a spelling mistake.

   ## Solution

   Change contributon to contribution.
   ```

10. Use the description's **Preview** tab to check the paragraphs and headings. Select **Create pull request** to submit. Open **Files changed** to confirm the correction. Keep the link to your pull request so you can return to it.

**Final check:** your pull request should be open and contain only the intended correction. Point to the changed line and explain what you corrected. Check that the base is Tobias's training repository. Has its original file changed yet? **No:** the pull request proposes the change; merging would apply it. Practice pull requests stay open so everyone can use the same starting files. Please do not merge them.

If you cannot find the comparison, open the original training repository, select **Pull requests → New pull request → compare across forks**, and choose the repositories and branches listed in step 7. If GitHub shows an existing pull request for your branch, open it instead of creating another.

## Another way to contribute

An **issue** describes a problem; a **pull request** supplies the proposed file edit. If you want to practise reporting the typo instead, open [Issues → New issue](https://github.com/TobiasNyhuus/github-training/issues/new/choose) and choose **Report a practice typo**. State the file, the current word, and your suggested correction. This is useful contribution practice, but it is not completion of the pull request exercise. Nothing in the file changes just because you submit an issue.

GitHub also offers a shorter editing route: open a file in someone else’s repository and select the pencil. It can offer to create a fork as part of editing. Use the numbered route above during this session so everyone can check the same steps.

## Optional second edit

In your existing `fix-contribution-spelling` branch, edit `practice.md` again. Replace the link text `Click here` with `Nordic Accessibility Community Group`, keeping the web address unchanged. Preview and commit the edit on the same branch. Return to your existing pull request and notice that it now includes both edits. Update its title and description to cover both changes.

## If you need help

Tell Tobias which step you reached, or describe what you expected to happen. You can use speech or chat. If sign-in, forking, or editing prevents you from completing the exercise, identify the correction and guide Tobias through the steps while he operates GitHub. This is supported practice; you can return later to complete the workflow independently.

If your fork or working branch already exists, reuse it to continue unfinished work. To start again, select your fork's `main` and create a fresh branch name, such as `fix-contribution-spelling-2`. Use that name wherever the exercise names the working branch. If GitHub offers an existing pull request for your branch, open it.

## Examples from the group's work

- [Community repositories](https://github.com/Nordic-Accessibility-Community-Group)
- [EN 301 549 resources and EAA monitoring](https://github.com/Nordic-Accessibility-Community-Group/en-301-549-resources-and-eaa-monitoring)
- [Pull request 27: Remove comma from URL](https://github.com/Nordic-Accessibility-Community-Group/en-301-549-resources-and-eaa-monitoring/pull/27) shows a small correction that was merged.
- [Accessibility conferences and events](https://github.com/Nordic-Accessibility-Community-Group/accessibility-conferences) has issue forms for **Suggest a conference or event** and **Report a conference correction**. Open **Issues → New issue** to find them. Submit real suggestions there; keep practice submissions in this training repository.
- [Community discussions about EN 301 549](https://github.com/Nordic-Accessibility-Community-Group/en-301-549-resources-and-eaa-monitoring/discussions) are for general questions and discussion. Use issues in that repository for suggested repository changes.

## For the facilitator

Use [demo.md](demo.md) and a fresh branch such as `fix-demo-spelling-live`. Correct `usefull` to `useful`, preview, commit and open a pull request with **TobiasNyhuus/github-training:main** as base. You already own this repository, so your demonstration can use a branch here. Participants first make their own fork; show and explain that additional step before demonstrating the edit.

Keep all demonstration and practice pull requests open. Leave both deliberate typos on `main` available to the next participant. Do not sync or merge the organisation’s copy during the workshop. The repository’s **Pull requests** tab contains the ready demonstration when available.

The exercise follows GitHub’s [browser pull request quickstart](https://docs.github.com/en/pull-requests/get-started/pull-request-quickstart) and [file editing instructions](https://docs.github.com/en/repositories/working-with-files/managing-files/editing-files). Button wording can vary slightly.
