# Sendgrid Email Form
## Description
A basic email form that uses sendgrid for email form submission. An implementation of a common feature using a Node/Express framework.

## Background
Starting out in web dev, email form submissions were one of the most challenging things for me to figure out an implementation for. I figured out one once before...but unfortunately time passed and I forgot how.

I originally sought to use nodemailer, however I found that it needed proper SMTP configs for usage with Gmail users so that didn't suit me a a universal application, especially being so unfamiliar with the tech and the process.

Sendgrid gave exactly what I was looking for - a straightforward, simple implementation that worked universally.

Long story short - I created this in case I ever forgot again how to do a simple email form submit in Node/Express, and for anyone else who finds themselves in the same boat.

## Installation
The central component of this app is Sendgrid. Read about it [here](https://sendgrid.com/)

To run this example, simply run

```bash
npm i
```

in your terminal.

## Roadmap

* REFACTOR.

Other than that, it's uncertain. Could go one of two ways:

* Improve upon the visuals and turn it into a template website w/ form submission for inquiries

Or,

* Simplify and refactor it into a proper lightweight npm module.


