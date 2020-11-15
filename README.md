# Requirements for Commit Names

#### init: - используется для начала проекта/таска. Примеры:
+ init: start youtube-task
+ init: start mentor-dashboard task

#### feat: - это реализованная новая функциональность из технического задания, (добавил поддержку зумирования, добавил footer, добавил карточку продукта). Примеры:

+ feat: add basic page layout
+ feat: implement search box 
+ feat: implement request to youtube API
+ feat: implement swipe for horizontal list
+ feat: add additional navigation button
+ feat: add banner
+ feat: add social links
+ feat: add physical security section
+ feat: add real social icons

#### fix: - исправил ошибку в ранее реализованной функциональности. Примеры:

+ fix: implement correct loading data from youtube
+ fix: change layout for video items to fix bugs
+ fix: relayout header for firefox
+ fix: adjust social links for mobile

#### refactor: - новой функциональности не добавлял / поведения не менял. Файлы в другие места положил, удалил, добавил. Изменил форматирование кода (white-space, formatting, missing semi-colons, etc). Улучшил алгоритм, без изменения функциональности. Примеры:

+ refactor: change structure of the project
+ refactor: rename vars for better readability
+ refactor: apply eslint
+ refactor: apply prettier

#### docs: - используется при работе с документацией/readme проекта. Примеры:

+ docs: update readme with additional information
+ docs: update description of run() method.


## Examples

#### fix: minor typos in code
* fixes task #3
* fixes task #7

---

#### chore(readme): fix consistency/appearance
* Make some minor changes to improve consistency and appearance. (Fix some weird brackets, and styling in the thank you section)

---

#### docs: adding Conventional Commits Next Version
* Adding the tool Conventional Commits Next Version to the tooling section.

---

#### build(deps): bump elliptic in /themes/conventional-commits
* Bumps [elliptic](https://github.com/indutny/elliptic) from 6.5.2 to 6.5.3.
* [Release notes](https://github.com/indutny/elliptic/releases)
* [Commits](indutny/elliptic@v6.5.2...v6.5.3)

---

#### Signed-off-by: dependabot[bot] <support@github.com>
* Co-authored-by: dependabot[bot] <49699333+dependabot[bot]@users.noreply.github.com>

---

#### docs(tooling): add several tools to the list
* Add the following tools for Conventional Commits:
    * commitizen/cz-cli
    * commitizen-tools/commitizen
    * commitlint
    * gitlint
    * semantic-release

--- 

#### fix(ko): improve and add translation
* add translation translations for related tools and project
improve a translation in faq

---

#### fix(example): present tense imperative (#19)
* "adds ability" -> "add ability".
