# Ghostreader Prompts

This repo contains a collection of user-created custom prompts for Readwise Reader ChatGPT-reading assistant `Ghostreader`.

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

More information on custom prompts can be found [here](https://readwise.io/reader/shared/01gr4nfn83amwaxps2nd8gjf5n/).

## Purpose

The purpose of this repo to collect and share custom prompts for `Ghostreader` that anyone can copy and paste into their custom prompt option in the 'Ghostreader' drop-down menu. See below:

![ghostreader-prompt](/images/ghostreader-prompt-screenshot.jpg)

## Organization

The custom prompts are organized into a single folder called 'prompts' with sub-folders organized based on their general purpose like 'summary', 'questions', and 'poems'. I imagine these sub-folders will expand and change as individuals contribute more prompts to the project.

## Contributing

Contributuons are welcome!

I'm still working on how best to organize the repository for ease of discoverability, so if you have suggestions please make a comment in the discussions section of this project.

As of right now, please add your prompt into a text file (ext ".txt") and follow these steps to contribute a custom prompt.

**Steps:**

1. Name file with ".txt' extension and give it a descriptive title that is not already taken like `short-summary-documents.txt`

2. ```text
    {#-
    author: <author's name>
    source: <url to source>
    -#}

    <prompt goes here>
    ```
