<div align="center">

<h1 style="border-bottom: none">
    <b><a href="#">Personal Portfolio
    </a></b>
</h1>

Personal - Portfolio is a fully responsive personal portfolio single-page website, responsive for all devices, built using HTML, CSS, JavaScript and Python.

Live Preview: 👉🏽 [personal-portfolio.githu.io](https://luisgtzb.github.io/LuisGTZ/)

![Made-with-python](https://img.shields.io/badge/Made%20with-Python-orange)
[![Jinja](https://github.com/ivansaul/personal-portfolio/actions/workflows/jinja.yml/badge.svg)](https://github.com/ivansaul/personal-portfolio/actions/workflows/jinja.yml)
![GitHub repo size](https://img.shields.io/github/repo-size/ivansaul/personal-portfolio)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


</div>

---

## Demo
<<<<<<< HEAD
![Demo](![Alt text](image.png))

=======
![Demo](![image](https://github.com/LuisGTZB/LuisGTZ/assets/64428694/f62814b6-f512-4fa8-afb2-eb3a4a4ef500)
)
>>>>>>> 308986da3d2eb2f6aff36bd88d5b24637b3a98ac

## **How to make it yours?** 

### Step 1: 
Fork this project and rename the repo to `your_github_username.github.io`.

For example: `LuisGTZ -> LuisGTZ.github.io`

### Step 2:
Go to the `config/` folder and replace the default data with your personal information.

```bash
config
|-- assets
|   |-- avatars
|   |-- icons
|   |-- posts
|   |-- projects
|-- about.toml
|-- blog.toml
|-- softskills.toml
|-- doing.toml
|-- projects.toml
|-- resume.toml
|-- social.toml
|-- technologies.toml
```

For example, to set your contact information, edit `config/about.toml`.

```toml
name = "Luis Gutiérrez! "
rol = "Data Scientist"
email = "email@example.com"
phone = "+52 (xxx) xxx-xxxx"
birthday = "May x, xxxx"
location = "León, Guanajuato, México"
avatar = "./config/assets/avatars/your_profile_pic.jpg"
```

### Step 3:
Create a personal access token.

`Settings(Account) > Developer settings > Personal access tokens > tokens (classic) > Generate new token > Generate new token (classic) `

- [x] Expiration: No expiration

### Step 4: 
Create a new secret with the name `PORTFOLIO_TOKEN` and paste your personal token there.

`Settings(Repo) > Secrets and Variables > Actions > Repository secrets > New secret`

### Step 5: 
Enable read and write permissions on:

`Settings(Repo) > Actions > General > Workflow permissions > Read and write permissions > save`

### Step 6: 
Enable GitHub Pages on:

`Settings(Repo) > Pages > Branch > Master > /(root > save`

### Step 7: 
Enable workflows on:

`Actions(Repo) > I understand my workflows, go ahead and enable them`

### Step 8: Enjoy 😉
Now you can visit your portfolio at `https://your_github_username.github.io`

Your personal portfolio will be built and updated automatically whenever any changes occur in the configuration files.

## Credits
This project is based on [vcard portfolio](https://github.com/codewithsadee/vcard-personal-portfolio). The main focus of this project is adding new features and make it accessible to everyone.

## License

MIT

[vcard]: https://github.com/codewithsadee/vcard-personal-portfolio
[devfolio]: https://luisgtzb.github.io/LuisGTZ/

