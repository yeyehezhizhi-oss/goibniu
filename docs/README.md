# goibniu — User Guide

goibniu is a simple, fast kanban app. You organize work into **projects**;
each project is a **board** of **columns** holding **cards**. Cards carry a
description, comments, labels, due dates, an assignee, and file attachments,
and everything updates live for everyone looking at the board.

This guide is for people using goibniu day to day. If you run the server,
see the project [`README`](../README.md) for setup and configuration.

## Contents

1. [Getting started](getting-started.md) — signing in and your first project
2. [Projects & boards](projects-and-boards.md) — columns, cards, drag & drop, live updates
3. [Card details](card-details.md) — the card panel: description, assignee, labels, due dates, moving
4. [Writing & mentions](writing-and-mentions.md) — the editor, formatting, `@`people and `#`cards, shortcuts
5. [Comments & attachments](comments-and-attachments.md) — discussing cards and attaching files
6. [Members & roles](members-and-roles.md) — inviting people and what each role can do
7. [Your account](account.md) — profile, theme, and API tokens
8. [The API](api.md) — automating goibniu with a token
9. [For administrators](admin.md) — creating accounts and managing the system

## A few things worth knowing up front

- **You don't sign up — an administrator creates your account.** You sign in
  with the email address they used; there's no password (see
  [Getting started](getting-started.md)).
- **Anyone with an account can create their own projects** and invite others.
- **Roles are per project.** You might be an Owner of one board and a Viewer
  of another. See [Members & roles](members-and-roles.md).
- **Light or dark** — toggle any time with the sun/moon button in the top-right.
