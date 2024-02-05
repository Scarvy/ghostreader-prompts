# Ghostreader Prompts

This repo contains a collection of custom `ghostreader` prompts for Readwise Reader.

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
