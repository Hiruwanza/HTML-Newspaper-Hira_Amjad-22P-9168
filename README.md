# HTML Newspaper Recreation - 

## Student Information
**Name:** Hira Amjad
**Roll Number:** 22P-9168
**Section:** BCS-8A

## Original Newspaper
**Name:** Nawa-i-Waqt (The Voice of Time)
**Date:** August 16, 1946
**Source:** [Scanned Archive (File: 22P-9168.jpg)](https://digitallibrary.punjab.gov.pk/handle/1/117895)

## Project Description
This project involves the recreation of the front page of the "Nawa-i-Waqt" Urdu newspaper, originally published on August 16, 1946. The goal was to replicate the complex, multi-column layout of a pre-1990s broadsheet using only semantic HTML5 and inline CSS, without external stylesheets or JavaScript. The text has been translated from Urdu to English, covering historical events such as the Quaid-e-Azam's meeting with Nehru and post-war diplomatic talks.

## Features Implemented
* **Semantic HTML5:** utilized tags like `<header>`, `<nav>`, `<article>`, `<section>`, and `<footer>` for better document structure.
* **Table Layout:** Implemented a standard HTML `<table>` to achieve the strict 3-column newspaper grid required by the assignment.
* **Inline Styling:** Used `style=""` attributes to control typography, borders (double and solid), and spacing to mimic the original aesthetic.
* **Image Handling:** Included a masthead and article images with `alt` attributes and grayscale filters to match the vintage look.
* **Complex Headers:** Nested tables within the header to align the date, price, and volume information accurately.

## Challenges Faced
The primary challenge was maintaining the rigid structure of the newspaper columns without using modern CSS Layouts like Flexbox or Grid. This was solved by using a table with `vertical-align: top` on cells to ensure articles started at the correct height. Additionally, recreating the "boxed" look of specific sub-sections (like the "Urgent Notice") required careful nesting of `div` elements with specific border styles within the table cells.