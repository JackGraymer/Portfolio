# 📓 Portfolio

This project is part of the open source curriculum from [The Odin Project](https://www.theodinproject.com) to study and become a <strong>full stack web Developer</strong>. 

For this project, [Astro.js](https://astro.build/) is the framework chosen, promises super fast build and loading times, perfect for an application like this, where the main purpose is to show a static HTML and very few times some JS.

>If you find yourself interested, check the [live Portfolio](https://jackgraymer.github.io/portfolio/) and find a quick preview of me on my [Github](https://github.com/JackGraymer)

---

## 👨‍💻 Alvaro Cervan - Full Stack Web Developer

I decided to become a teacher right before finishing high-school. Studied a bachelor in sport science and a masters in education.

I loved being a **teacher**, but reality was that most of my time and childhood, I  spent with a computer, watching series, playing games, studying or researching new things.

At some point, giving it a shot to become a developer just made sense. Wasted loads of time trying to choose the *best language*, finding the *best tutorial / course* etc.
Finally, found an open source project to become a Full Stack Web Developer, and there in the rabbit hole I went.

Nowdays I enjoy a lot making sites and web apps, and it is very satisfying using this knowledge to help friends or satiate clients.

It is fascinating how many tools and frameworks are available and the new ones that come up. 
Now it is clear that the most famous it is not always the best, that all have their pros and cons and that it absolutely depends on the project and your goals.

## 🚀 Project 

As mentioned the portfolio is made with `Astro`.
Astro uses it's own syntax and components, but works similar to `React` as in components`.astro` define a module to be exported and inserted in your document.

The difference is that Astro creates static files on build, so the site ends up with simple `HTML` and `CSS` and minimal to no `JS`, reducing size and loading times.

> Astro components can be written in `HTML` or `markdown`, and for some reason, I **LOVE `markdown`** 

<br>

<details>
<summary> Development </summary>

### Astro

`Astro` allows to use a `layout` as a template, to share components among the pages. In this case is usefull for the header as an example.

This portfolio has only 2 pages, the `index` one is made by several `astro components` imported in order. 
Each component will be styled individually and only global styles will be on a separace `CSS` file.

### About page

The about page is the same as the [README](https://github.com/JackGraymer/JackGraymer/blob/main/README.md) from my Github profile.
After making a few changes, realized that having to update the files manually in 2 different repos is an unnecessary extra effort.

The idea then would be to use `JS` to fetch the file from Github and load it.
It was not that easy. 

Astro did not have documentation about this, as they allow import of local `.md` files, but nothing about fetching it.

After a lot of googling, came across that this is not an Astro issue, is a `NodeJS` issue. Not having a Dom changes a lot of things.

The easy solution with `vanilla JS` would have been using `DOMParser` but this is not available. After an `NPM` install and an import, all works as it should have.

Almost easy peasy, now the **about** page is loaded with JS from Github (increases loading time) but it is worth the miliseconds in exchange of updating and pushing manually both files.

</details>

<br>

## 📞 Contacts
<ul>
<li><strong><a href="mailto:&#97;&#99;&#x65;&#114;&#118;&#97;&#110;&#x63;&#x61;&#110;&#116;&#x6f;&#x6e;&#x40;&#x67;&#x6d;&#x61;&#x69;&#x6c;&#x2e;&#x63;&#111;&#x6d;">&#97;&#99;&#x65;&#114;&#118;&#97;&#110;&#x63;&#x61;&#110;&#116;&#x6f;&#x6e;&#x40;&#x67;&#x6d;&#x61;&#x69;&#x6c;&#x2e;&#x63;&#111;&#x6d;</a></strong></li>
<li><strong><a href="https://www.linkedin.com/in/alvaro-cervan-canton-1085551b3/">LinkedIn</a></strong></li>
<li><strong><a href="https://github.com/JackGraymer">Github</a></strong></li>
</ul>