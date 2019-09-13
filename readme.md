<h1 align="left">
    Meetapp Backend NodeJS
</h1>

<h4 align="lef">
  This is a developer event aggregator app called Meetapp (an acronym for Meetup + App).
</h4>

<p align="left">
<img alt="GitHub top language" src="https://img.shields.io/github/languages/top/ewersoncastelo/meetapp-backend.svg">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/ewersoncastelo/meetapp-backend.svg">
 <a href="https://www.codacy.com/manual/ewersoncastelo/meetapp-backend?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=ewersoncastelo/meetapp-backend&amp;utm_campaign=Badge_Grade"><img src="https://api.codacy.com/project/badge/Grade/278b57830ba040b6a3a3a9d351008920"/></a>
<a href="https://github.com/ewersoncastelo/meetapp-backend/blob/master/LICENSE"><img alt="GitHub license" src="https://img.shields.io/github/license/ewersoncastelo/meetapp-backend"></a>
<a href="https://github.com/ewersoncastelo/meetapp-backend/issues">
    <img alt="Repository issues" src="https://img.shields.io/github/issues/ewersoncastelo/meetapp-backend.svg">
  </a>
    <img alt="Repository size" src="https://img.shields.io/github/repo-size/ewersoncastelo/meetapp-backend.svg">
  <a href="https://github.com/ewersoncastelo/meetapp-backend/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/ewersoncastelo/meetapp-backend.svg">
  </a>
</p>

## Installation

+ [Express](https://expressjs.com/)
+ [Bcrypt](https://www.npmjs.com/package/bcrypt)
+ [BeeQueue](https://github.com/bee-queue/bee-queue)
+ [DateFns](https://date-fns.org/)
+ [Dotenv](https://www.npmjs.com/package/dotenv)
+ [Jsonwebtoken](https://jwt.io/)
+ [Mongoose](https://www.mongodb.com/)
+ [Nodemailer](https://nodemailer.com/about/)
+ [Sequelize](https://sequelize.org/)
+ [Yup](https://www.npmjs.com/package/yup)
+ [VSCode][vc] with [EditorConfig][vceditconfig] and [ESLint][vceslint]
+ [Insomnia][inso]

## Software Required

To access the routes (post, get, update, ..), download the [Insomnia][inso] and your prefer Data Base for the run ```yarn migrate```, the settings the insomnia can be found in the root of the project.

To perform tests on the api routes follow the following steps:

- Run the program and click on the Main Logo
- Then click the import/export option and import the file **insomia-test.json**

## How To Use

This App requires [Node][nodejs] v4+ and [Yarn][yarnpkg] to run.

Open your favorite Terminal and run these commands. Navigate to the project folder and run the following command to install the dependencies:

```bash
# Clone this repository
$ git clone https://github.com/ewersoncastelo/meetapp-backend

# Go into the repository
$ cd meetapp-backend

# Install dependencies
$ yarn install

# Run migrations to your database
$ yarn migrate

# Run the server and queue
$ yarn dev
$ yarn queue
```

---

## License

This project is under the [MIT LICENSE](https://github.com/ewersoncastelo/meetapp-backend/blob/master/LICENSE) for more information.

---

[nodejs]: https://nodejs.org/
[yarnpkg]: https://yarnpkg.com/
[vc]: https://code.visualstudio.com/
[vceditconfig]: https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig
[vceslint]: https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint
[inso]: https://insomnia.rest/download/
