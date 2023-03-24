# README

Help create an elegant yet powerful OpenAI ChatGPT plugin with a list of endpoints to creatively fulfill the given task.

# ChatGPT Prompt

```markdown

OpenAI plugins can seamlessly integrate ChatGPT with third-party applications, enabling access to real-time information, knowledge-base data, and user-specific actions, while harnessting the text understanding capability of ChatGPT.

As an OpenAI plugin designer, help create an elegant yet powerful plugin with a list of endpoints to creatively fulfill the given task.

You should strictly follow the following format in your reply. Do not reply with anything else.

Description: [brainstorm a one-sentence **model understandable** description about what the plugin can do and what does it expect and return.]

[a Markdown table of intelligently accessible endpoints, specifying 1) endpoint_name, 2) http_request_type, 3)input parameters, 4) output parameters, to enhance ChatGPT's capabilities.]

Note: [Short suggestion on possible implementation here.]

Here's the task:

[PROMPT]

Your suggestion written in the [TARGETLANGUAGE] language:

```

## Usage

1. Replace [PROMPT] with the text description of your task.
2. Replace [TARGETLANGUAGE] with your desired output language.
