---
title: "Connections Pre-Event Practice IETF Draft"
abbrev: "Pre-Event Practice Draft"
category: info

docname: draft-stark-connections-pre-event-draft-latest
v: 3
area: CONNECTIONS
workgroup: PRE-EVENT
keyword: Internet-Draft

author:
 -
    fullname: Barbara Stark
    organization: None (Retired)
    email: "bhstark2@users.noreply.github.com"

normative:

informative:


--- abstract

Connections participants would like some simple instruction in creating IETF drafts. This draft tries to provide that.


--- middle

# Introduction

Connections participants would like some simple instruction in creating IETF drafts. This draft tries to provide that by providing important links and basic information. This draft doesn't actually use any normative language, but has left the boilerplate for that in the next section, for grins and giggles.

# Conventions and Definitions

{::boilerplate bcp14-tagged}

# Connections pre-event-preparation

## Signing up for a GitHub (GH) account

Everyone needs a GitHub account to contribute to a draft being written in GitHub. To set up a GH account, go to <https://github.com/> and enter a preferred username, the email address you want to associate with the account (personal or work, depending on preferences and your corporate policies), and a password. GH will impose username uniqueness and password strength.

## Signing in to GH

The <https://github.com/> page defaults to "Sign Up". Click "Sign In" at the upper right to get the "Sign In" page if you already have an account.

# Topics we will cover

## Setting up the GitHub repository

This will set up a repository and draft template for automated IETF markdown -> xml and html generation.

Note: Only one person needs to do this, and not all authors of a draft.

Start from: <https://github.com/martinthomson/i-d-template/blob/main/doc/TEMPLATE.md>

Consider bookmarking this. All other steps flow from here.

You should see the rendered README.md below the list of files at this URL. If not, scroll down to it. Do step 1 (including clicking on the link), which says: Create a new repository using the template. Check "Include all branches", or you will need to enable GitHub Pages manually after step 2.

And then do step 2: Rename your draft and add a title.

You're now ready to edit your draft and add collaborators/authors.

## Adding collaborators / authors

Repository default settings allow anyone logged in to GH to create a fork of the repository, make changes in their fork, and then create a Pull Request (PR). But that's not a great experience for novice collaborators. Get the GH account names of your collaborators and explicitly add them to the repository Collaborator list (there should be a little gear symbol with "Settings" next to it in the top menu for your repo -- Collaborators is the first option listed in the left menu of Settings). If you trust your collaborators to follow your rules, you should give them Editor privilege.

## Other Settings

You'll see there are a lot of Settings you can play with, depending on how people are behaving and other preferences. A couple of settings I like:

- in General (towards the bottom): Automatically delete head branches
- in Branches, branch protection rules for Main branch: Require a pull request before merging 

## Rules I've used with great success

These rules assume the person is a Collaborator with Editor privilege. I provide the following 2 paragraphs as rules to my collaborators.

In the repository, click on the file you want to edit, and then click on the pencil icon in the upper right of the file. Do your edits. When done, scroll to the bottom of the page, select the checkbox that says "Create a new branch for this commit and start a pull request" (this is really important), and click on the "Propose Changes" button. If the button says "Commit Changes" instead of "Propose Changes", then you need to click the "Create a new branch for this commit and start a pull request" button first. On the next page that appears, click "Create pull request". If you think some description of your changes might help, feel free to enter something in the "Leave a comment" box (either for Propose Changes or the Pull Request).

If you want to work on the Pull Request (PR) over time or provide additional edits to your existing PR, you can do this at any time before the PR is merged. To do this, you simply edit files in your newly created branch. Select your branch from the pulldown menu (default branch in the pulldown is "Main") at the upper left of the repository Code page. The pulldown menu is located right under the <> Code tab heading. 

## Kramdown-rfc markdown

There are many flavors of markdown. There is no single markdown "standard" (i.e., there are many markdown standards). Most have similar (but not identical) syntax rules.

The template uses kramdown-rfc: <https://github.com/cabo/kramdown-rfc>. There is another flavor of markdown that also has support for RFC metadata. But kramdown-rfc is well-supported for IETF drafts,  works great, is easy to use and learn, and the template is already formatted for it.

## Basic markdown syntax

See <https://kramdown.gettalong.org/syntax.html#structural-elements>. But the main thing you need to know is to put blank lines between paragraphs. There are 2 header styles supported. Pick one and be consistent.

## IETF metadata

See <https://github.com/cabo/kramdown-rfc#the-yaml-header> for the draft document metadata (draft title, authors, date, etc.).

See <https://github.com/cabo/kramdown-rfc#references> for formatting references. Referencing IETF RFCs and drafts is incredibly easy, thanks to the great tools that make magic happen behind the scenes.

## Generating the xml, txt, and html

This all happens like magic with every merged pull request, thanks to the automated workflows Martin has in that i-d-template repo we started from.

# Security Considerations

Use GitHub repository Settings to secure access to your draft. You can even make it private, if you don't want anyone to see it. Be careful doing that, though, because GH sets a max storage limit on private repos.


# IANA Considerations

This document has no IANA actions.


--- back

# Acknowledgments
{:numbered="false"}

Obviously, we have to thank Martin Thomson and Carsten Bormann for the amazing tools that make this all work.
