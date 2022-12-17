# NS Editing

First, to anyone choosing to contribute to __New Spectrum__ in any way, I would like to thank you in advance. As for those who go the extra mile to help with documentation and Wiki pages, you are doing me a tremendous favor.

That said, as __New Spectrum__ is an Organization, professionalism is important. Humor is welcome, as you've probably noticed, but ultimately we aim to produce __high quality code & documentation with *uniform* construction and formatting__.

The key word there is __*Uniform*__, because (as you're probably aware) there are dozens- if not *hundreds* of ways to accomplish the same goal. More to the point, there are *hundreds* of ways to __organize the same exact code__ being used to execute that code.

So, for the sake of our potential users (not to mention *our* own sanity), it is *crucial* that we all maintain the following...

- __File System Organization__
- __Core Document/File Layouts__
- __Basic Formatting Rules__
	- Do __*not*__ use __[Prettier]__ (unless specifically instructed to)
	- Do __*not*__ use a *Format on Save* feature
		- I am planning on building an auto-formatting extension for Visual Studio Code that can be used in place of __[Prettier]__ or the default formatter.
		- Eventually I plan on extending this to the following applications (in this order):
			1. __[Visual Studio]__
			2. __[Acode for Android]__
			3. __[Xcode for MacOS]__

	

<br />

---

# Links & Citations

It's *very* important that __we provide links to any and all internal *or* external resources__. *Especially* internal resources. Look at how __[Wikipedia](https://wikipedia.org/)__ does it. The only difference is we likely won't be adding the small __[Numeric Footnote Citations](https://www.markdownguide.org/extended-syntax/#footnotes)__ that *would* link to the __[Bibliography]__ at the bottom. I would *like* to include them, and maybe I'll jury-rig them into Wikis later on, but the default syntax isn't supported by __[GitHub Flavored Markdown (GFM)](https://github.github.com/gfm)__.

## Adding Links

When you add links, whether it's to an __[Internal Resource]__ or an __[External Resource]__, the first thing you do is __*Put the*__ `Link Title` __*in* [Bold Brackets]__.

It doesn't matter if you have the necessary URL right away- __I don't even care if you publish without adding a URL at first__. But if you do, *add an issue to make sure they get completed by you or someone else*. So long as they're marked __[Like This]__, it's an easy task.

__Hunting down URLs before you continue is a great way to halt your progress and kill your motivation.__

Now, this is how you add your references...

### External Resources

Now, if you don't know how to create an __[Embedded URL/URI Link]__ in Markdown, this is the syntax:

```markdown
[Displayed Text](https://github.com)
```

However, *our* links/references will be bolded, like so:

```markdown
__[Displayed Text](https://github.com)__
```

### Internal Resources

Fortunately all __[Internal Resources]__ will have a very uniform __[URL Scheme]__.

