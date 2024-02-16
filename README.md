# Ghostreader Prompts

A collection of user-created prompts for [Reader's](https://readwise.io/read) "Copilot of Reading" feature - **Ghostreader**.

![ghostreader-prompt](/images/ghostreader-prompt-screenshot.jpg)

## Purpose

To collect, share, and collaborate on prompts.

## About using custom prompts in `Ghostreader`

> **Directly from Readwise Reader:**
>
> {#- ⚠️ Custom prompts are an advanced feature. ⚠️
> Custom prompts enable you to interface with GPT-3 directly using variables for content contained in the document such as the title, the whole text, the focused paragraph, a text selection, your highlights, and more. This is done using the Jinja templating language.
>
> See reference documentation for more instructions on how to use custom Ghostreader prompts. The default example below writes a haiku based on your highlights. -#}
>
> I took the following highlights while reading a document titled {{ document.title }}:
>
> """
> {% for highlight in highlights %}
> {{ highlight.content }} {{ "\n\n" }}
> {% endfor %}
> """
>
> Write a haiku.

For more information on custom prompts and the Ghostreader feature in general. Please refer to this newsletter [here](https://readwise.io/reader/shared/01ha2p6ej8fke512v151ngvx3n).

## Folder Structure

The prompts are organized into a single folder called **"prompts"** with sub-folders organized based on their general purpose like **"summary"**, **"questions"**, and **"poems"**. I imagine these sub-folders will expand and change as individuals contribute more prompts to the project.

I'm still working on how best to organize the repository for ease of discoverability. If you have any suggestions please on how best to organize everything please make a comment in the **"Discussions"** section of this project or in the Reader Discord channel **"#ghostreader-gpt"**.

## User-Guide

Under the "Wiki" tab, there is a user-guide with descriptions of parameters to help craft prompts.

## Contributing

Contributions are welcome!

As of right now, please paste your prompt into a text file (ext ".txt") and follow these steps to contribute a custom prompt.

**Steps:**

1. Name file with ".txt' extension and give it a descriptive title that is not already taken like `short-summary-documents.txt`

2. ```text
    {#-
    author: <author's name>
    source: <url to source (if applicable)>
    -#}

    <prompt goes here>
    ```
