# WEB102 Prework - Sea Monster Crowdfunding App

Submitted by: **George Cadel-Munoz**

**Name of your app** is a website for the company Sea Monster Crowdfunding that
displays information about the games they have funded.

Time spent: **4** hours spent in total

## Required Features

The following **required** functionality is completed:

- [x] The introduction section explains the background of the company and how
      many games remain unfunded.
- [x] The Stats section includes information about the total contributions and
      dollars raised as well as the top two most funded games.
- [x] The Our Games section initially displays all games funded by Sea Monster
      Crowdfunding
- [x] The Our Games section has three buttons that allow the user to display
      only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

- [x] Performed a CSS update to change the feel of the website.
- [x] Added a search function to find games by title.
- [x] Added naviggation and action button to take user to listed games.

## Video Walkthrough

Check out the short video demo here:

<video width="320" height="240" controls>
  <source src="Sea Monster site demo.mp4" type="video/mp4">
</video>

## Notes

Some of the challenges I ran into while building this application included using
the provided data located in the **games.js** file. Without adjusting the
formatting, the original code in **index.js** parses JSON twice, throwing an
error. I simply changed the variable _GAMES_JSON_ to be set as the value of
_GAMES_DATA_ since it was already in JSON format.

## License

    Copyright 2025 George Cadel-Munoz

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
