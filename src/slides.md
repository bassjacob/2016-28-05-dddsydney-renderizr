class: title

# Jacob's Lambda

&nbsp;

## Serverless Component Rendering a la carte

---

class: middle

.left[
# $ whoami

## Jacob Bass
]

.right[

## @bassjacob

## bassjacob@gmail.com

## github.com/subshad

## http://jacobbass.net
]

---

class: middle, center

# Domain.com.au

---

class: middle

# Tooling

# Front End Ops

# Developer Experience (DX)

---

class: section

# Project Complexity

---

class: middle, image-background
background-image: url('public/monolith.jpg')

.right.white-title.dark-mask[
# One project
# One codebase
]

---

class: middle, image-background
background-image: url('public/spaghetti.jpg')

.right.white-title.dark-mask[
# One project
# Many codebases
]

---

class: middle, image-background
background-image: url('public/modularity.jpg')

.right.white-title.dark-mask[
# Many projects
# Many codebases
]

---

class: center, middle, image-background
background-image: url('public/microservices.jpg')

.dark-mask.pull-left.white-title[
## I know, I'll use microservices...
]

---

class: sub-section

# How do we server-side render JS on non-nodejs platforms?

---

class: center, middle

<img style="width: 60%" src="public/nope.gif">

---

class: sub-section

# How do we update nested component dependencies?

---

class: center, middle

<img style="width: 60%" src="public/whackamole.gif">

---

class: sub-section

# What do we do if something breaks?

---

class: center, middle

<img style="width: 70%" src="public/throwingcomputer.gif">

---

class: section

# What might a solution look like?

---

class: middle

## Reusable components between .red[pages]

## Reusable components between .red[languages]

## Components rendered on the .red[server] and .red[client]

---

class: center, middle, image-background
background-image: url('public/lambda_react.svg')

---

Why AWS Lambda?

---

Why ReactJS?

---

class: section

# RenderizrJS

&nbsp;

&nbsp;

&nbsp;

## When all you have is a lambda, everything starts to look stateless

---

Registry

---

Module

---

Conductor

---

Example workflow

---

class: center, middle

# Features

## * Distributed

## * SSR - Universal

## * Non-runtime specific

## * Reusable components between everything!

---

class: section

# Demo

---

class: section

# Caveats

---

class: center

# Regional Support

# Sleepytime

# Latency

---

class: section

# ToDo

---

class: center

# CSS/SCSS and CSS Modules support

# Validation of components interop

# Dynamic global requirements

# SystemJS ?

---

class: section

# QnA

---

class: center, middle, image-background
background-image: url('public/ddd_sponsors.svg')

