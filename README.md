
nginx
======

<table style="width:100%">
  <tr>
    <td>
       <a href="https://slim.ai" title="title">
         <img src="https://github.com/slimdevl/markdown-hacks/blob/master/image/getstarted.png" alt="size metrics" title="" />
       </a>
    </td>
  </tr>
</table>

<table style="width:100%">
  <tr>
    <td>
       <a href="https://slim.ai" title="title">
         <img src="https://github.com/slimdevl/markdown-hacks/blob/master/image/metric1.png" alt="size metrics" title="" />
       </a>
    </td>
    <td>
       <a href="https://slim.ai" title="title">
         <img src="https://github.com/slimdevl/markdown-hacks/blob/master/image/metric2.png" alt="size metrics" title="" />
       </a>
    </td>
    <td>
       <a href="https://slim.ai" title="title">
         <img src="https://github.com/slimdevl/markdown-hacks/blob/master/image/metric3.png" alt="size metrics" title="" />
       </a>
    </td>
  </tr>
</table>

<table style="width:100%">
  <tr>
    <td>
       <a href="https://slim.ai" title="title">
         <img src="https://github.com/slimdevl/markdown-hacks/blob/master/image/volumes.png" alt="size metrics" title="" />
       </a>
    </td>
  </tr>
  <tr>
    <td>
       <a href="https://slim.ai" title="title">
         <img src="https://github.com/slimdevl/markdown-hacks/blob/master/image/shells.png" alt="size metrics" title="" />
       </a>
    </td>
  </tr>
  <tr>
    <td>
       <a href="https://slim.ai" title="title">
         <img src="https://github.com/slimdevl/markdown-hacks/blob/master/image/permissions.png" alt="size metrics" title="" />
       </a>
    </td>
  </tr>
  <tr>
    <td>
       <a href="https://slim.ai" title="title">
         <img src="https://github.com/slimdevl/markdown-hacks/blob/master/image/labels.png" alt="size metrics" title="" />
       </a>
    </td>
  </tr>
  <tr>
    <td>
       <a href="https://slim.ai" title="title">
         <img src="https://github.com/slimdevl/markdown-hacks/blob/master/image/environment_vars.png" alt="size metrics" title="" />
       </a>
    </td>
</table>

---
# What is this?

This repository contains the image documentation for each of the official images. See [docker-library/official-images](https://github.com/docker-library/official-images) for more information about the program in general.

All Markdown files here are run through [tianon's fork of `markdownfmt`](https://github.com/tianon/markdownfmt), and verified as formatted correctly via GitHub Actions.

-	[![GitHub CI status badge](https://img.shields.io/github/workflow/status/docker-library/docs/GitHub%20CI/master?label=GitHub%20CI)](https://github.com/docker-library/docs/actions?query=workflow%3A%22GitHub+CI%22+branch%3Amaster)
-	[![library update.sh status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/docs/job/library.svg?label=Automated%20library%20update.sh)](https://doi-janky.infosiftr.net/job/docs/job/library/)
	-	[![amd64 update.sh status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/docs/job/amd64.svg?label=Automated%20amd64%20update.sh)](https://doi-janky.infosiftr.net/job/docs/job/amd64/)
	-	[![arm32v5 update.sh status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/docs/job/arm32v5.svg?label=Automated%20arm32v5%20update.sh)](https://doi-janky.infosiftr.net/job/docs/job/arm32v5/)
	-	[![arm32v6 update.sh status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/docs/job/arm32v6.svg?label=Automated%20arm32v6%20update.sh)](https://doi-janky.infosiftr.net/job/docs/job/arm32v6/)
	-	[![arm32v7 update.sh status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/docs/job/arm32v7.svg?label=Automated%20arm32v7%20update.sh)](https://doi-janky.infosiftr.net/job/docs/job/arm32v7/)
	-	[![arm64v8 update.sh status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/docs/job/arm64v8.svg?label=Automated%20arm64v8%20update.sh)](https://doi-janky.infosiftr.net/job/docs/job/arm64v8/)
	-	[![i386 update.sh status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/docs/job/i386.svg?label=Automated%20i386%20update.sh)](https://doi-janky.infosiftr.net/job/docs/job/i386/)
	-	[![ppc64le update.sh status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/docs/job/ppc64le.svg?label=Automated%20ppc64le%20update.sh)](https://doi-janky.infosiftr.net/job/docs/job/ppc64le/)
	-	[![s390x update.sh status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/docs/job/s390x.svg?label=Automated%20s390x%20update.sh)](https://doi-janky.infosiftr.net/job/docs/job/s390x/)
	-	[![windows-amd64 update.sh status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/docs/job/windows-amd64.svg?label=Automated%20windows-amd64%20update.sh)](https://doi-janky.infosiftr.net/job/docs/job/windows-amd64/)

## Table of Contents

<!-- AUTOGENERATED TOC -->

1.	[What is this?](#what-is-this)
	1.	[Table of Contents](#table-of-contents)
2.	[How do I update an image's docs](#how-do-i-update-an-images-docs)
3.	[How do I add a new image's docs](#how-do-i-add-a-new-images-docs)
4.	[Files related to an image's docs](#files-related-to-an-images-docs)
	1.	[folder `<image name>`](#folder-image-name)
	2.	[`README.md`](#readmemd)
	3.	[`content.md`](#contentmd)
	4.	[`README-short.txt`](#readme-shorttxt)
	5.	[`logo.png`](#logopng)
	6.	[`license.md`](#licensemd)
	7.	[`maintainer.md`](#maintainermd)
	8.	[`github-repo`](#github-repo)
	9.	[`user-feedback.md`](#user-feedbackmd)
5.	[Files for main Docs repo](#files-for-main-docs-repo)
	1.	[`update.sh`](#updatesh)
	2.	[`generate-repo-stub-readme.sh`](#generate-repo-stub-readmesh)
	3.	[`push.pl`](#pushpl)
	4.	[`.template-helpers/generate-dockerfile-links-partial.sh`](#template-helpersgenerate-dockerfile-links-partialsh)
	5.	[`.template-helpers/template.md` and `.template-helpers/user-feedback.md`](#template-helperstemplatemd-and-template-helpersuser-feedbackmd)
6.	[Issues and Contributing](#issues-and-contributing)

<!-- AUTOGENERATED TOC -->

# How do I update an image's docs

Edit the `content.md` for an image; not the `README.md` as it's auto-generated from the contents of the other files in that repo. To see the changes to the `README.md`, run `./update.sh myimage` from the repo root, but do not add the `README.md` changes to your pull request. See also `markdownfmt.sh` point [below](#how-do-i-add-a-new-images-docs).

After opening your Pull Request the changes will be checked by an automated `markdownfmt.sh` before it can be merged. A common issue is incorrect spacing such as with two lines missing an empty line between them (double-spaced).

# How do I add a new image's docs

-	create a folder for my image: `mkdir myimage`
-	create a `README-short.txt` (required, 100 char max)
-	create a `content.md` (required)
-	create a `license.md` (required)
-	create a `maintainer.md` (required)
-	create a `github-repo` (required)
-	add a `logo.png` (recommended)

Optionally:

-	run `./markdownfmt.sh -l myimage` to verify whether format of your markdown files is compliant to `tianon/markdownfmt`. In case you see any file names, markdownfmt detected some issues, which might result in a failed build during continuous integration. run `./markdownfmt.sh -d myimage` to see a diff of changes required to pass.
-	run `./update.sh myimage` to generate `myimage/README.md` for manual review of the generated copy.
	**Note:** do not actually commit the `README.md` file; it is automatically generated/committed before being uploaded to Docker Hub.

# Files related to an image's docs

## folder `<image name>`

This is where all the partial and generated files for a given image reside, (ex: `golang/`).

## `README.md`

This file is generated using `update.sh`.

## `content.md`

This file contains the main content of your image's long description. The basic parts you should have are a "What Is" section and a "How To" section. See the doc on [Official Repos](https://docs.docker.com/docker-hub/official_repos/#a-long-description) for more information on long description. The issues and contribution section is generated by the script but can be overridden. The following is a basic layout:

```markdown
# What is XYZ?

// about what the contained software is

%%LOGO%%

# How to use this image

// descriptions and examples of common use cases for the image
// make use of subsections as necessary
```

## `README-short.txt`

This is the short description for the docker hub, limited to 100 characters in a single line.

> Go (golang) is a general purpose, higher-level, imperative programming language.

## `logo.png`

Logo for the contained software. While there are not hard rules on formatting, most existing logos are square or landscape and stay within a few hundred pixels of width.

## `license.md`

This file should contain a link to the license for the main software in the image. Here is an example for `golang`:

```markdown
View [license information](http://golang.org/LICENSE) for the software contained in this image.
```

## `maintainer.md`

This file should contain a link to the maintainers of the Dockerfile.

## `github-repo`

This file should contain the URL to the GitHub repository for the Dockerfiles that become the images. The file should be in a single line ending in a newline with no extraneous whitespace. Only one GitHub repo per image repository is supported. It is used in generating links. Here is an example for `golang`:

```text
https://github.com/docker-library/golang
```

## `user-feedback.md`

This file is an optional override of the default `user-feedback.md` for those repositories with different issue and contributing policies.

# Files for main Docs repo

## `update.sh`

This is the main script used to generate the `README.md` files for each image. The generated file is committed along with the files used to generate it (see below on what customizations are available). Accepted arguments are which image(s) you want to update or no arguments to update all of them.

This script assumes [`bashbrew`](https://github.com/docker-library/official-images/tree/81e90ca8dcec892ade7eb348cba5a4a5d6851e17/bashbrew) is in your `PATH` (for scraping relevant tag information from the library manifest file for each repository).

## `generate-repo-stub-readme.sh`

This is used to generate a simple `README.md` to put in the image's repo. Argument is the name of the image, like `golang` and it then outputs the readme to standard out.

## `push.pl`

This is used by us to push the actual content of the READMEs to the Docker Hub as special access is required to modify the Hub description contents.

## `.template-helpers/generate-dockerfile-links-partial.sh`

This script is used by `update.sh` to create the "Supported tags and respective `Dockerfile` links" section of each generated `README.md` from the information in the [official-images `library/` manifests](https://github.com/docker-library/official-images/tree/master/library).

## `.template-helpers/template.md` and `.template-helpers/user-feedback.md`

These files are the templates used in building the `<image name>/README.md` file, in combination with the individual image's files.

# Issues and Contributing

If you would like to make a new Official Image, be sure to follow the [guidelines](https://docs.docker.com/docker-hub/official_repos/).

Feel free to make a pull request for fixes and improvements to current documentation. For questions or problems on this repo come talk to us via the `#docker-library` IRC channel on [Freenode](https://freenode.net) or open up an issue.