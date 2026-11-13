# Unlocking the Bible: Student Study Guide

A study guide website for students taking the **Unlocking the Bible** course (Lessons 1–10 and 12).

**Live site:** https://loisdlr.github.io/unlocking-the-bible/

## What's inside each lesson

- **Study:** lesson notes, the passages to read, and a "Go deeper" panel explaining each passage with its historical background
- **Key points:** practise the fill-in-the-blank key statements from the class handout
- **Word studies:** Hebrew and Greek words as flip cards
- **Background:** history and culture behind the lesson
- **Questions:** common questions with answers
- **Charts:** every chart from the lesson, viewable full screen
- **Quiz:** a 6-question self-check
- **My notes:** private notes, saved in your browser only

The site also has a scripture index of every passage in the course (in Bible order) and a search box.

## How it works

It is a single self-contained `index.html` with no build step and no server. Progress and notes are stored in each student's own browser (`localStorage`). Nothing is sent anywhere.

## Updating

Replace `index.html` with a new build and push to `main`. GitHub Pages republishes automatically within a minute or two.
