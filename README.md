# permutator
A simple website for permutating strings.  Useful for creating utterance variations for your intents on Alexa.  Tested using Chrome on a Mac.  Here's a live version:

https://rejamison.github.io/permutator/

<img width="1155" alt="screen shot 2016-09-30 at 9 09 12 am" src="https://cloud.githubusercontent.com/assets/1970771/18998455/9acd58b0-86ed-11e6-84bc-2d4fc839c3cf.png">

# Usage

1. Type in the name of your intent and some variations on the utterances you plan to use.  I recommend breaking your sentance down into parts, like each noun, verb, etc.  The sample utterance output will update as you type.
2. If you want the sample utterances to include phrases that get skipped over (i.e., want [find][it] to generate both "find" and "find it") add an empty line to the text area.
3. Click copy to grab the sample utterance block to your clipboard.
4. Note that the block includes a commented out link.  That link can be used to get back to the current state of the tool so you can refine the output later.

# Acknowledgements

Thanks to JQuery BBQ, for their URL parameter module, which is used to grab content from the URL params.  https://github.com/cowboy/jquery-bbq
