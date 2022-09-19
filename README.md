
My 100-days-of-code followed the scheduled is as per the task list below. I had split the 100-days into 15-20 specific topics, each topic stretching to at least 5 days. 

### Notes

1. Since I wanted to learn Azure and pass some of their certifications, those are some of the topics considered, you can leave them out and replace them with your own tasks from your bucket-list.
1. Salesforce Commerce Cloud (SFCC) tasks can also be left out & replaced with other tasks specific to the topic.

## Planning the Tasks & Topics for 100 Days

This itself is a task on its own which is not listed but were done the days preceding the "marathon". You would also need to do this planning on your own if you are changing any topics are tasks.

### Setup CI/CD Server & Write scripts to handle check-ins

- [ ] Setup GoCD server in DigitalOcean with the PostgreSQL & Analytics extension
    * Find out how to model manual testing in GoCD pipeline.
    * Setup GoCD pipelines & scripts to track the time spent on completing courses. This is to be done in [online-course-notes repo]().
    * Setup GoCD pipeline for this repo with the script to update the daily task(s) status' & track the time spent on each one using the [GTM](https://github.com/git-time-metric/gtm) utility and also its [vim plugin](https://github.com/git-time-metric/gtm-vim-plugin).


### Vim, VimScript and its Configuration

- [ ] Install Vim & setup markdown plugins - markdown preview in browser
    * There are quite a few of them: [vim-livedown](https://github.com/shime/vim-livedown) for [livedown](https://github.com/shime/livedown), [vmd](https://github.com/yoshuawuyts/vmd), [vim-instant-markdown](https://github.com/instant-markdown/vim-instant-markdown), [markdown-preview](https://github.com/yuanchuan/markdown-preview) - archived, python based [grip](https://github.com/joeyespo/grip), [gfms](https://github.com/pawel-wiejacha/gfms), [octodown](https://github.com/ianks/octodown)
    * Only Octodown (600+ stars), vim-instant-markdown (2.6k stars) and grip (5.8k stars) have recent commits in 2022.
    * Going with vim-instant-markdown since it also supports diagramming markup using mermaid.
- [ ] Install & setup minimal configuration for langs JS, JSX, Typescript, Lua, ISML, XML, YAML, JSON, Golang and Kotlin.
    * [Deoplete](https://github.com/Shougo/deoplete.nvim) or [CoC](https://github.com/neoclide/coc.nvim) - which one? Not sure if any one has compared but many suggest to use CoC, [reddit thread](https://www.reddit.com/r/vim/comments/ares04/deoplete_vs_cocnvim/) asking for suggestions.
    * The Deoplete git repo recommends moving to [DDC](https://github.com/Shougo/ddc.vim) which is based on [Deno](https://deno.land) and [denops.vim](https://github.com/vim-denops/denops.vim).
    * Do we need the above plugins if we use LSP server & one of client plugins? Looks like CoC is also an LSP client.
    * Which LSP client plugin ? [vim-lsc](https://github.com/natebosch/vim-lsc) or [vim-lsp](prabirshrestha/vim-lsp) - Comments in [vim-lsc issue #279](https://github.com/natebosch/vim-lsc/issues/279) suggest to use vim-lsc, but no comments in [vim-lsp issue ##816](https://github.com/prabirshrestha/vim-lsp#816).
    * LSP in vim with [LSC Plugin](https://bluz71.github.io/2019/10/16/lsp-in-vim-with-the-lsc-plugin.html).
- [ ] Get familiar with Vim pure editing: [key bindings](https://hea-www.harvard.edu/~fine/Tech/vi.html) and language specific key bindings.
- [ ] Write script to show the DW-API docs on function name hover in vim-lsp, check [this issue #275](https://github.com/prabirshrestha/vim-lsp#275).
- [ ] Setup neovim with fuzzy finder & LSP using [this video](https://www.youtube.com/watch?v=FW2X1CXrU1w)
- [ ] Setup plantuml rendering using [this plgin](https://github.com/weirongxu/plantuml-previewer.vim) and syntax highlight.
- [ ] Setup ISML file syntax highlighter - need to check if there is any ftplugin.

### Azure AI Fundas Certification Prep (AI-900)

- [ ] Watch the [4 hours prep video](https://www.youtube.com/watch?v=OwZHNH8EfSU&t=8s) from freecodecamp.
- [ ] Go through the [AI-900 Exam study guide](https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RE4wGpB)
- [ ] Go thru' sections: Intro to "Funda principles of ML on Azure" in [this Udemy course](https://www.udemy.com/course/azure-ai-fundamentals/) - total *5 hours*.
- [ ] Watch the remaining sections in the above course - total *4.5 hours*
- [ ] Take the mock exam(s) in the above course

### Learning REST API & GraphQL

TODO

### Azure Data Fundas (DP-900) Certification Prep

- [ ] Sections Intro to "How to work with Rel Data" in Azure Data Fundas [Udemy Course](https://www.udemy.com/course/azure-dp-900/) - total *3 hours*.
- [ ] Sections "How to work with Non-Rel data" to "Analytics workload" in above course - total *4.5 hours*.

- [ ] Read the [study guide](https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RE4wsKZ) for [Azure Data Fundas - DP-900](https://learn.microsoft.com/en-gb/certifications/exams/dp-900)
- [ ] Take the two mock exams in the above Udemy course

### Azure Fundamentals Certification Prep (AZ-900)

- [ ] Watch & take notes from [this FreeCodeCamp youtube video](https://www.youtube.com/watch?v=NKEFWyqJ5XA) - total *3 hours*
- [ ] Browse thru' the [official study guide](https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RE3VwUY)
- [ ] Skim thru' the 3 learning paths (11 modules) in [this official exam page](https://learn.microsoft.com/en-us/certifications/exams/az-900)

### Kubernetes for Developers (CKAD Certification)

- [ ] Go through the section 1 (Intro) to "Observability" section - total 4 hours in [Udemy CKAD Course](https://www.udemy.com/course/certified-kubernetes-application-developer/)
- [ ] Watch & take notes from section "POD Design" to "State Persistence" - total 4 hours
- [ ] Watch the sections "Updates for Sep 2021" to "Lightning Labs" - total 4 hours
- [ ] Review & take the mock exam #1
- [ ] Review & take the mock exam #2

### Learn Graph Extension for Redis

- [ ] Install Redis & the required graph extension & create a simple graph
- [ ] Write nodejs script to extract code dependencies
- [ ] Create a simple web app to query the Redis graph dats-structures
    * Do not spend much time on the browser front-end

### Learn CSS3 and Tailwind Library

- [ ] [CSS: Inheritance, specificity & cascade](https://www.linkedin.com/learning/css-inheritance-specificity-and-the-cascade), LinkedIn learning
- [ ] [Tailwind CSS3 essential training](https://www.linkedin.com/learning/tailwind-css-3-essential-training), LinkedIn learning

### Learn HTTP2, HTML5 and Javascript for Front-end

- [ ] Learn about HTTP2 protocol
    * Check what protocol messages help in async download of large files after generation
    * How HTTP2 helps in streaming?
- [ ] [Semantic HTML & CSS code challenges](https://www.linkedin.com/learning/semantic-html-and-css-code-challenges), LinkedIn learning
- [ ] Learn HTML5 tags (TODO: decide the sub-set)
- [ ] Javascript for the browser: events, etc.
- [ ] [HTML & CSS Creating forms](https://www.linkedin.com/learning/html-css-creating-forms)
- [ ] PDF generation from the browser - order invoice example
    * Some references: [jsPDF example](https://phppot.com/javascript/html-to-pdf-in-javascript-using-jspdf/), [jsPDF how-to](https://phppot.com/javascript/convert-html-to-pdf-using-jspdf-javascript-library/)
- [ ] PDF generation on the server-side, required for example for gift certificate.
    * [pdf-lib](https://github.com/Hopding/pdf-lib) with no dependencies, [doc/help](https://pdf-lib.js.org/docs/help)

### Learn Python & Flask

- [ ] Pick one of the "Core Python" book or online course and read a few topics.
- [ ] Learn about the basics of Flask web framework.
- [ ] Implement a streaming interface for browsing graph data using [iterfzf](https://github.com/dahlia/iterfzf) or [pyfzf](https://github.com/nk412/pyfzf).

### Learn Ruby & Rails

- [ ] Read chapter 2 in the book [Seven languages in 7 weeks](https://www.oreilly.com/library/view/seven-languages-in/9781680500059)
- [ ] Code review of open-source code of [Redmine](https://github.com/redmine/redmine)
- [ ] Watch the railscasts video on Rails introduction
- [ ] Write a Redmine plugin to do the following features which helps in CI/CD integration:
    * Add a new state for version called "UAT-Ready"
    * Call a webhook when a *version* is set to *locked* 
    * Call a webhook when a *version* is set to *UAT-Ready*
    * References: [Diff. between locked/closed](https://www.redmine.org/boards/2/topics/18914), [Versions vs. milestones](https://www.redmine.org/boards/1/topics/214?page=3), [issue #13387](https://www.redmine.org/issues/13387)

### Learn Golang

- [ ] Go thru' the [Getting started with Go](https://www.coursera.org/learn/golang-getting-started?specialization=google-golang) in coursera specialisation](https://www.coursera.org/specializations/google-golang#courses)
- [ ] Take the 2nd course [Functions, methods & Interfaces](https://www.coursera.org/learn/golang-functions-methods?specialization=google-golang) in [coursera specialisation](https://www.coursera.org/specializations/google-golang#courses)
- [ ] Complete the 3rd course [Concurrency in Go](https://www.coursera.org/learn/golang-concurrency?specialization=google-golang)
- [ ] Code review of open source tool fzf written in Go.

### Learn Kotlin

- [ ] Weeks 1-3 from the course [Kotlin for Java developers](https://www.coursera.org/learn/kotlin-for-java-developers#syllabus)
- [ ] Chapters 1-5 from the book [Kotlin in Action (1st Ed)](https://livebook.manning.com/book/kotlin-in-action-second-edition)
- [ ] Chapters 6-9 from the book [Kotlin in Action (1st Ed)](https://livebook.manning.com/book/kotlin-in-action/about-this-book/)
- [ ] Chapter 10-11 from the book & Kotlin Concurrency
- [ ] Code review of open-source app (TODO-link) written in Kotlin

### Learn Functional Scala & Spark

- [ ] [Functional programming principles in Scala](https://www.coursera.org/learn/scala-functional-programming?specialization=scala) in [Functional prog. in scala specialisation](https://www.coursera.org/specializations/scala#courses) in Coursera.
- [ ] [Functional program design in Scala](https://www.coursera.org/learn/scala-functional-program-design?specialization=scala) in [Functional prog. in scala specialisation](https://www.coursera.org/specializations/scala#courses) in Coursera.
- [ ] [Parallel Programming](https://www.coursera.org/learn/scala-parallel-programming?specialization=scala) in the Coursera specialisation.
- [ ] [Big data analysis with Scala & Spark](https://www.coursera.org/learn/scala-spark-big-data?specialization=scala) in the Coursera specialisation.

### Learn Haskell

- [ ] Study [chapter 8](https://learning.oreilly.com/library/view/seven-languages-in/9781680500059/f_0050.html) from the book: Seven languages in 7 weeks.
- [ ] Watch the first 6 modules in [this youtube videos](https://www.classcentral.com/course/youtube-functional-programming-in-haskell-59638)
- [ ] Watch the 7 to 12th modules in [this youtube videos](https://www.classcentral.com/course/youtube-functional-programming-in-haskell-59638)
- [ ] Watch the 13th to 16th modules in [this youtube videos](https://www.classcentral.com/course/youtube-functional-programming-in-haskell-59638)

## Learning After 100 Days

### Learn Prolog

- [ ] Read [chapter 4](https://learning.oreilly.com/library/view/seven-languages-in/9781680500059/f_0026.html) in the book [Seven languages in 7 weeks](https://www.oreilly.com/library/view/seven-languages-in/9781680500059)

