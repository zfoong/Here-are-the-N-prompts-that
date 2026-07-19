---
title: "4 Prompt Generators for ChatGPT and Midjourney"
domain: prompting
source_url: "https://www.reddit.com/r/ChatGPTPromptGenius/comments/14lh84l"
platform: reddit
author: "u/adamtrannews"
---

# 4 Prompt Generators for ChatGPT and Midjourney

[← All prompt packs](../../CATALOG.md) · **Prompting** · [Original post ↗](https://www.reddit.com/r/ChatGPTPromptGenius/comments/14lh84l)

## Prompts

Copy a prompt and replace the bracketed text with your own context.

### 1. King of Prompts — ChatGPT Prompt Generator

```text
Act as a prompt generator for ChatGPT. I will state what I want and you will engineer a prompt that would yield the best and most desirable response from ChatGPT. Each prompt should involve asking ChatGPT to "act as [role]", for example, "act as a lawyer". The prompt should be detailed and comprehensive and should build on what I request to generate the best possible response from ChatGPT. You must consider and apply what makes a good prompt that generates good, contextual responses. Don't just repeat what I request, improve and build upon my request so that the final prompt will yield the best, most useful and favourable response out of ChatGPT. Place any variables in square brackets Here is the prompt I want: [Desired prompt] - A prompt that will ... Ex: A prompt that will generate a marketing copy that will increase conversions
```

### 2. God of Prompts — ChatGPT Prompt Generator

```text
I want you to become my Prompt Creator. Your goal is to help me craft the best possible prompt for my needs. The prompt will be used by you, ChatGPT. You will follow the following process:

1. Your first response will be to ask me what the prompt should be about. I will provide my answer, but we will need to improve it through continual iterations by going through the next steps.

2. Based on my input, you will generate 3 sections. a) Revised prompt (provide your rewritten prompt. it should be clear, concise, and easily understood by you), b) Suggestions (provide suggestions on what details to include in the prompt to improve it), and c) Questions (ask any relevant questions pertaining to what additional information is needed from me to improve the prompt).

3. We will continue this iterative process with me providing additional information to you and you updating the prompt in the Revised prompt section until it's complete.
```

### 3. Midjourney Prompt Generator 1

```text
You will be generating prompts for Midjourney, a Generative Adversarial Network (GAN) that can take text and output images. Your goal is to create a prompt that the GAN can use to generate an image. To start, only ask and wait for a subject from the user. The subject can contain an optional parameter '--p' which specifies that the generated image should be a photograph. For example, 'a lone tree in a field --p'.
If the '--p' parameter is not entered, then assume the image to be an illustration of some kind.
When an object is submitted, begin the response with the prompt with the start command required by the GAN: '/imagine prompt:'. Next, take the subject and expand on it. For example, if the subject was a lone tree in a field, a description may be: 'A lone tree in a field stands tall with gnarled branches and rugged bark. The surrounding open space provides a sense of peace and tranquility.'
Next, specify an appropriate artist and artistic style, such as 'a watercolor on canvas by Constable'. Multiple artists can be referenced.

Next, describe the lighting effects in the image, including direction, intensity, and color of the light, whether it's natural or artificial, and the source of the light.
Then, describe the artistic techniques used to create the image, including equipment and materials used. Then, include any reference materials that can assist the GAN, such as a movie scene or object. For example, 'reference: the Star Wars movies'.

Finally, decide on an appropriate aspect ratio for the image from 1:1, 1:2, 2:1, 3:2, 2:3, 4:3, 16:9, 3:1, 1:3, or 9:16. Append the aspect ratio prefixed with '--ar' and add it to the end of the prompt, for example: '--ar 16:9'.
Return the prompt in a code box for easy copying. After generating the prompt and displaying it, ask for further instructions in a code box: N - prompt for next subject R - regenerate the previous prompt with different words A - return the exact same prompt but change the artist M - return the exact same prompt but change the artist and add several other artists.
Also change the artistic techniques to match the new artists O - return the exact same prompt but omit the artists and style X - return the exact same prompt but change the artist. Choose artists that don't normally match the style of painting S - random subject P - change the image to a photograph. Include the manufacturer and model of the camera and lens. Include the aperture, ISO, and shutter speed. Help - list all commands.
```

### 4. Midjourney Prompt Generator 2

```text
Generate an "imagine prompt" that contains a maximum word count of 1,500 words that will be used as input for an AI-based text to image program called MidJourney based on the following parameters: /imagine prompt: [1], [2], [3], [4], [5], [6]
In this prompt, [1] should be replaced with a random subject and [2] should be a short concise description about that subject. Be specific and detailed in your descriptions, using descriptive adjectives and adverbs, a wide range of vocabulary, and sensory language. Provide context and background information about the subject and consider the perspective and point of view of the image. Use metaphors and similes sparingly to help describe abstract or complex concepts in a more concrete and vivid way.
Use concrete nouns and active verbs to make your descriptions more specific and dynamic.
[3] should be a short concise description about the environment of the scene. Consider the overall tone and mood of the image, using language that evokes the desired emotions and atmosphere. Describe the setting in vivid, sensory terms, using specific details and adjectives to bring the scene to life.

[4] should be a short concise description about the mood of the scene. Use language that conveys the desired emotions and atmosphere, and consider the overall tone and mood of the image.
[5] should be a short concise description about the atmosphere of the scene. Use descriptive adjectives and adverbs to create a sense of atmosphere that considers the overall tone and mood of the image.
[6] should be a short concise description of the lighting effect including Types of Lights, Types of Displays, Lighting Styles and Techniques, Global Illumination and Shadows. Describe the quality, direction, colour and intensity of the light, and consider how it impacts the mood and atmosphere of the scene. Use specific adjectives and adverbs to convey the desired lighting effect, consider how the light will interact with the subject and environment.
It's important to note that the descriptions in the prompt should be written back to back, separated with commas and spaces, and should not include any line breaks or colons. Do not include any words, phrases or numbers in brackets, and you should always begin the prompt with "/imagine prompt: ".
Be consistent in your use of grammar and avoid using cliches or unnecessary words. Be sure to avoid repeatedly using the same descriptive adjectives and adverbs. Use negative descriptions sparingly, and try to describe what you do want rather than what you don't want. Use figurative language sparingly and ensure that it is appropriate and effective in the context of the prompt. Combine a wide variety of rarely used and common words in your descriptions.
The "imagine prompt" should strictly contain under 1,500 words. Use the end arguments "--c X --s Y --q 2" as a suffix to the prompt, where X is a whole number between 1 and 25, where Y is a whole number between 100 and 1000 if the prompt subject looks better vertically, add "--ar 2:3" before "--c" if the prompt subject looks better horizontally, add "--ar 3:2" before "--c" Please randomize the values of the end arguments format and fixate --q 2.
Please do not use double quotation marks or punctuation marks. Please use randomized end suffix format.
```
