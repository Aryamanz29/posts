# Posts 📝
_Blogging seems easy with github 🤩_

A Headless CMS [(Github theme)](https://github.com/MeiK2333/github-style) using [Hugo](https://gohugo.io/), Github Issues and [Github Actions.](https://github.com/features/actions)

<p align="center">
<img src="https://user-images.githubusercontent.com/56113566/144758957-746eeff1-a859-4a02-8a6e-3b1f660c622c.png" alt="github-actions-png" height="200"></img>
<img src="https://user-images.githubusercontent.com/56113566/144759066-f5be8060-c278-490b-9bf0-9e664a5499da.jpg" alt="github-actions-png" height="200"></img>
</p>

![-------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## Features 📸

### Add Blog Posts ✏

This is very simple process, You only need to create an [issue](https://github.com/Aryamanz29/posts/issues/new/choose) using [create-a-post](https://github.com/Aryamanz29/posts/blob/master/.github/ISSUE_TEMPLATE/create-a-post.md) issue template.

![Screenshot from 2021-12-06 00-14-49](https://user-images.githubusercontent.com/56113566/144759404-563163dc-b9f0-4b15-a30f-386ed6798655.png)

![Screenshot from 2021-12-06 00-14-53](https://user-images.githubusercontent.com/56113566/144759405-cdb6e584-65d3-4c57-9239-430a7591e331.png)


### Edit Blog Posts 📎

![Screenshot from 2021-12-06 00-16-56](https://user-images.githubusercontent.com/56113566/144759456-1d9b593c-7333-4a4f-85c7-b11f18853476.png)


### Remove Blog Posts ❌

Just simply close that issue, See how easy is it 🙃

![Screenshot from 2021-12-06 00-19-02](https://user-images.githubusercontent.com/56113566/144759498-c5ac138b-bf35-4f9f-82b6-b7f5f96ee8fa.png)

### Preview Blog Posts 🎬

![Screenshot from 2021-12-06 00-17-04](https://user-images.githubusercontent.com/56113566/144759452-c895c181-653a-42bd-a124-6ec7519e67a5.png)

### Organize Blog Posts 📚

You could either **pin** your posts to the [home page](https://aryamanz29.github.io/posts/) or simple push that [all posts page](https://aryamanz29.github.io/posts//post/).

You only need to set `pin: true/false` in the issue template.

![Screenshot from 2021-12-06 00-27-43](https://user-images.githubusercontent.com/56113566/144759787-bf05c0d9-5fc2-44a9-aeb6-103d01e0a723.png) 

![-------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## Configuration 🛠

If you want to add this CMS in your repo , Do below steps ⬇

#### 1.Clone this repo 📥

```bash
git clone https://github.com/Aryamanz29/posts.git
```

#### 2.Change `config.toml` ✏

Just replace 
`YOUR_GITHUB_USERNAME` = Your github username
`YOUR_REPO_NAME` = Repository name
```toml
baseURL = "https://YOUR_GITHUB_USERNAME.github.io/YOUR_REPO_NAME"
languageCode = "en-us"
title = "Aryaman's blog"
theme = "github-style"

[params]
  author = "YOUR_NAME"
  description = "Blogs by Aryamanz29 👨‍💻, Built with Github Actions 🚀"
  github = "Aryamanz29"
  #facebook = ""
  twitter = "AryamanZ29"
  linkedin = "aryamanz29"
  instagram = "aryaman_z29"
  email = "aryamanz29@gmail.com"
  url = "https://aryamanz29.github.io/"
  lastmod = true
  userStatusEmoji = "🌠"
  favicon = "/posts/images/github.png"
  location = "India"
  
[frontmatter]
  lastmod = ["lastmod", ":fileModTime", ":default"]
```

#### 3. Change workflow files 📋

- `create-issue-posts.yml` **Line 36**:
```yml
hugo -D -b https://YOUR_GITHUB_USERNAME.github.io/YOUR_REPO_NAME/ -t github-style
```

- `remove-issue-posts.yml` **Line 31**:
```yml
hugo -D -b https://YOUR_GITHUB_USERNAME.github.io/YOUR_REPO_NAME/ -t github-style
```

4. And don't forgot to add [this](https://github.com/MeiK2333/github-style)  hugo theme and run local dev server to check everthing working as expected.

```bash
cd themes/
rm -rf github-style/
git clone https://github.com/MeiK2333/github-style.git
cd ..
hugo serve
``` 
![-------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)