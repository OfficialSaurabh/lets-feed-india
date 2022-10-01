# Hacktoberfest-2022 ✨✨
![192114009-0830321a-d227-4a4d-8411-6c03b54d7ce6](https://user-images.githubusercontent.com/31384539/193418327-827ccd84-6bd1-435d-a128-1272edf53324.png)

## Prerequisites:
* Install git in your machine.
* Have basic command line experiance.
* have knowledge of basic NextJs, TypeScript, Tailwind, tRPC

## What is Hacktoberfest? :thinking:
A month-long celebration from October 1st to October 31st presented by [Digital Ocean](https://hacktoberfest.digitalocean.com/) and [DEV Community](https://dev.to/) collaborated with [GitHub](https://github.com/blog/2433-celebrate-open-source-this-october-with-hacktoberfest) to get people involved in [Open Source](https://github.com/open-source). Create your very first pull request to any public repository on GitHub and contribute to the open-source developer community.

[https://hacktoberfest.digitalocean.com/](https://hacktoberfest.digitalocean.com/)

## Rules and Regulations

1. Pull requests can be submitted to any opted-in repository on GitHub or GitLab

2. The pull request must contain commits you made yourself.

3. If a maintainer reports your pull request as spam, it will not be counted toward your participation in Hacktoberfest.

4. If a maintainer reports behavior that’s not in line with the project’s code of conduct, you will be ineligible to participate.

5. To get a shirt, you must make four approved pull requests (PRs) on opted-in projects between October 1-31 in any time zone.

6. This year, the __first 40,000__  participants can earn a T-shirt.

### Examples of low quailty contributions

+ Pull requests that are automated e.g. scripted opening pull requests to remove whitespace / fix typos / optimize images.

+ Pull requests that are disruptive e.g. taking someone else's branch/commits and making a pull request.

+ Pull requests that are regarded by a project maintainer as a hindrance vs. helping.

+ Something that's clearly an attempt to simply +1 your pull request count for October.

+ Last but not least, one pull request to fix a typo is fine, but 5 pull requests to remove a stray whitespace is not.

# Steps For Contribution

```mermaid
flowchart LR
    Fork[Fork the project]-->branch[Create a New Branch]
    branch-->Edit[Edit file]
    Edit-->commit[Commit the changes]
    commit -->|Finally|creatpr((Create a Pull Request))
    
 ```

0. Star <a href="https://github.com/Feed-India/lets-feed-india" title="this">this</a> repository.

1. Fork <a href="https://github.com/Feed-India/lets-feed-india" title="this">this</a> repository.

2. Clone the forked repository.
```css
git clone https://github.com/<your-github-username>/Hacktoberfest-2022
```
  
3. Navigate to the project directory.
```py
cd Hacktoberfest-2022
```

4. Create a new branch.
```css
git checkout -b <your_branch_name>
```

5. Make changes.

6. Stage your changes and commit
```css
git add -A

git commit -m "<your_commit_message>"
```

7. Push your local commits to the remote repo.
```css
git push -u origin <your_branch_name>
```

8. Create a Pull Request.

9. Congratulations! 🎉 you've made your contribution.

# Create T3 App

This is an app bootstrapped according to the [init.tips](https://init.tips) stack, also known as the T3-Stack.

## Why are there `.js` files in here?

As per [T3-Axiom #3](https://github.com/t3-oss/create-t3-app/tree/next#3-typesafety-isnt-optional), we take typesafety as a first class citizen. Unfortunately, not all frameworks and plugins support TypeScript which means some of the configuration files have to be `.js` files.

We try to emphasize that these files are javascript for a reason, by explicitly declaring its type (`cjs` or `mjs`) depending on what's supported by the library it is used by. Also, all the `js` files in this project are still typechecked using a `@ts-check` comment at the top.

## What's next? How do I make an app with this?

We try to keep this project as simple as possible, so you can start with the most basic configuration and then move on to more advanced configuration.

If you are not familiar with the different technologies used in this project, please refer to the respective docs. If you still are in the wind, please join our [Discord](https://t3.gg/discord) and ask for help.

- [Next-Auth.js](https://next-auth.js.org)
- [Prisma](https://prisma.io)
- [TailwindCSS](https://tailwindcss.com)
- [tRPC](https://trpc.io) (using @next version? [see v10 docs here](https://trpc.io/docs/v10/))

Also checkout these awesome tutorials on `create-t3-app`.

- [Build a Blog With the T3 Stack - tRPC, TypeScript, Next.js, Prisma & Zod](https://www.youtube.com/watch?v=syEWlxVFUrY)
- [Build a Live Chat Application with the T3 Stack - TypeScript, Tailwind, tRPC](https://www.youtube.com/watch?v=dXRRY37MPuk)
- [Build a full stack app with create-t3-app](https://www.nexxel.dev/blog/ct3a-guestbook)
- [A first look at create-t3-app](https://dev.to/ajcwebdev/a-first-look-at-create-t3-app-1i8f)

## How do I deploy this?

### Vercel

We recommend deploying to [Vercel](https://vercel.com/?utm_source=t3-oss&utm_campaign=oss). It makes it super easy to deploy NextJs apps.

- Push your code to a GitHub repository.
- Go to [Vercel](https://vercel.com/?utm_source=t3-oss&utm_campaign=oss) and sign up with GitHub.
- Create a Project and import the repository you pushed your code to.
- Add your environment variables.
- Click **Deploy**
- Now whenever you push a change to your repository, Vercel will automatically redeploy your website!

### Docker

You can also dockerize this stack and deploy a container. See the [Docker deployment page](https://create-t3-app-nu.vercel.app/en/deployment/docker) for details.

## Useful resources

Here are some resources that we commonly refer to:

- [Protecting routes with Next-Auth.js](https://next-auth.js.org/configuration/nextjs#unstable_getserversession)
