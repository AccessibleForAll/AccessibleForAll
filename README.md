# License

MIT License

Copyright (c) 2023 Accessible For All

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


# Contributing to AccessibleForAll

## Languages

This project is built with Next.JS, Typescript and CSS modules.

## Pre-requisites (these need to be installed on your machine)

[Node.js](https://nodejs.org/en/)  
[Yarn Package Manager](https://yarnpkg.com/)  

## Available packages

Icons - [React Icons Documentation]( https://react-icons.github.io/react-icons)  
Code Snippets - [React Syntax Highlighter Documentation](https://github.com/react-syntax-highlighter/react-syntax-highlighter)  
Translations - [next-i18next Documentation](https://next.i18next.com/)  
Storybook - [Storybook Documentation](https://storybook.js.org/)

## How to contribute

1.  Look through [Pre-existing issues](https://github.com/AccessibleForAll/AccessibleForAll/issues) or [Raise a new issue](https://github.com/AccessibleForAll/AccessibleForAll/issues/new) and ask to be assigned. Pull requests made without a corresponding issue will likely be closed.
2. Please check the [coding standards](https://github.com/AccessibleForAll/AccessibleWebDev/blob/main/CODING_STANDARDS.md) page before start contributing.
3.  [Fork](https://github.com/AccessibleForAll/AccessibleForAll/fork) the project
4.  Clone the project:
    ```bash
    git clone https://github.com/<your-github-username>/AccessibleForAll
    ```
5.  Navigate to the project directory:
    ```bash
    cd AccessibleForAll
    ```
6.  Set the upstream repository:
    ```bash
    git remote add upstream https://github.com/AccessibleForAll/AccessibleForAll.git
    ```
7.  Install dependencies:
    ```bash
    yarn install
    ```
8.  Create a new branch:
    ```bash
    git checkout -b <YourBranchName>
    ```
9.  To run the whole project locally:
    ```bash
    yarn dev
    ```
    If you are making an isolated component and wish to run storybook locally instead of the whole website run this instead of `yarn dev`:
    ```bash
    yarn storybook
    ```

10.  Make your changes
11. Stage your changes:
    ```bash
    git add <NameOfFileChanged>
    ```
12. Commit your changes:
    ```bash
    git commit -m "<Your commit message here>"
    ```
13. Push your commits to your local repository
    ```bash
    git push origin <YourBranchName>
    ```
14. Create a [pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)
15. Wait for maintainers to review your pull request and suggest any changes

**Congratulations!** You made a contribution to the Accessible For All Community!

## Questions?

If at any time you need help with contributing, please reach out to the [maintainers](https://github.com/AccessibleForAll/Support/blob/main/README.md#our-maintainers)
