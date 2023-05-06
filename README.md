# Project Lyrics App

The app shown in the code is a music player application built with React and Redux. The app allows users to search for and play music, view details about tracks and artists, and discover new music.

While the app has similar features to Spotify, it is important to note that it is not a direct competitor to Spotify and may not be better in all respects. Spotify is a well-established music streaming service that provides access to millions of songs, while the app shown in the code is a smaller-scale project focused on implementing a music player with limited features.

That being said, the app shown in the code may be beneficial for those who prefer a simpler, more lightweight music player without the need for a full-fledged music streaming service. Additionally, the app is open source, allowing developers to customize and extend its features as needed.

# Contributing

When contributing to this repository, please first discuss the change you wish to make via issue.
Please note we have a [code of conduct](CODE_OF_CONDUCT.md), please follow it in all your interactions with the project.

# Functionality
This component uses the following components and pages:

# Components
1. _Searchbar:_ A component that displays a search input field.
2. _Sidebar:_ A component that displays a navigation menu.
3. _MusicPlayer:_ A component that displays the music player controls.
4. _TopPlay:_ A component that displays a list of top tracks.
 
# Pages
1. _Discover:_ The home page of the application.
2. _TopArtists:_ A page that displays a list of top artists.
3. _TopCharts:_ A page that displays a list of top tracks.
4. _AroundYou:_ A page that displays artists around the user's location.
5. _ArtistDetails:_ A page that displays details about an artist.
6. _SongDetails:_ A page that displays details about a track.
7. _Search:_ A page that displays search results based on a user's input.

The component fetches the activeSong data from the Redux store, and renders the components and pages based on the user's navigation. The Routes component from react-router-dom is used to render different pages based on the user's navigation.

When a user plays a track, the MusicPlayer component is displayed at the bottom of the screen, and the TopPlay component is displayed on the right-hand side of the screen.


## System Requirements

To get started with development, you need to install few tools

1. git 
   
   `git` version 2.13.1 or higher. Download [git](https://git-scm.com/downloads) if you don't have it already.

   To check your version of git, run:

   ```shell
    git --version
   ```

2. node 
   
   `node` version 16.15.1 or higher. Download [node](https://nodejs.org/en/download/) if you don't have it already.

   To check your version of node, run:

   ```shell
    node --version
   ```

3. npm
  
   `npm` version 5.6.1 or higher. You will have it after you install node.

   To check your version of npm, run:

   ```shell
    npm --version
   ```

## Setup

To set up a development environment, please follow these steps:

1. Clone the repo

   ```shell
    git clone https://github.com/JavaScript-Mastery-PRO/project1_team4_repository.git
   ```

2. Change directory to the project directory

    ```shell
    cd project1_team4_repository
    ```

3. Install the dependencies
   
    ```shell
     npm install
    ```

    If you get an error, please check the console for more information.

    If you don't get an error, you are ready to start development.

4. Run the app
   
    ```shell
    npm run dev
    ```

    Project will be running in the browser.

    Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

## Issues

You've found a bug in the source code, a mistake in the documentation or maybe you'd like a new feature? You can help us by [submitting an issue on GitHub](https://github.com/orgs/JavaScript-Mastery-PRO/projects/8). Before you create an issue, make sure to search the issue archive -- your issue may have already been addressed!

Please try to create bug reports that are:

- _Reproducible._ Include steps to reproduce the problem.
- _Specific._ Include as much detail as possible: which version, what environment, etc.
- _Unique._ Do not duplicate existing opened issues.
- _Scoped to a Single Bug._ One bug per report.


## Pull Request

There are 2 main work flows when dealing with pull requests:

* Pull Request from a [forked repository](https://help.github.com/articles/fork-a-repo)
* Pull Request from a branch within a repository

Here we are going to focus on 2. Creating a Topical Branch:


1. First, we will need to create a branch from the latest commit on master. Make sure your repository is up to date first using

   ```bash
    git pull origin main
   ```

   *Note:* `git pull` does a `git fetch` followed by a `git merge` to update the local repo with the remote repo. For a more detailed explanation, see [this stackoverflow post](http://stackoverflow.com/questions/292357/whats-the-difference-between-git-pull-and-git-fetch).

2. To create a branch, use `git checkout -b <new-branch-name> [<base-branch-name>]`, where `base-branch-name` is optional and defaults to `main`. 
   
   Use a standard convention for branch names. For example, `<your-name>-dev`. It will be easier to track your pull requests if you use this convention.
   
   I'm going to create a new branch called `jsm-dev` from the `main` branch and push it to github.

   ```bash
    git checkout -b jsm-dev main
    git push origin jsm-dev
   ```

3. To create a pull request, you must have changes committed to your new branch.

4. Go to [Pull Requests](https://github.com/JavaScript-Mastery-PRO/project1_team4_repository/pulls) and click on the `New Pull Request` button.

5. Select the `main` branch as the `base` branch and the `jsm-dev` branch as the `compare` branch.

6. Follow the template and fill in the proper information for the pull request.

7. Click on the `Submit` button.

8. You have successfully created a pull request. Now wait for mentor approval. Once approved, you can merge the pull request.

#
## NB

1. Use non run dev to start server. 
2.The project uses Tailwind.

#Tailwind

Tailwind is a utility-first CSS framework designed to speed up the process of creating custom web designs. Unlike traditional CSS frameworks that focus on pre-designed components and templates, Tailwind provides a set of pre-defined utility classes that can be used to quickly style HTML elements.

The idea behind Tailwind is to provide a comprehensive set of CSS classes that map directly to commonly used CSS properties. This allows developers to focus on designing their UI without worrying about the specifics of CSS, and without having to write custom CSS for every element on the page.

Some of the key benefits of using Tailwind include:

- Faster development: With Tailwind, developers can create custom designs much faster than with traditional CSS frameworks, as they can simply apply pre-defined classes to their HTML elements.
- Consistent design: By using a set of standardized utility classes, Tailwind ensures that the UI will look consistent across the entire application, even if it has been designed by different developers.
- Customizability: Tailwind provides a wide range of configuration options that allow developers to customize the framework to fit their specific needs, including the ability to define custom utility classes.

Overall, Tailwind is a powerful tool that can help developers create beautiful, functional, and consistent UI designs quickly and efficiently.
