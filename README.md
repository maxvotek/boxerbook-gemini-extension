# Boxerbook extension for Gemini CLI

Connects Gemini CLI to the public [Boxerbook](https://boxerbook.com) MCP server (`https://mcp.boxerbook.com/mcp`, Streamable HTTP, no authentication): boxing schedules, results, boxer records, bouts, rankings and where to watch.

## Install

```
gemini extensions install https://github.com/maxvotek/boxerbook-gemini-extension
```

## Example prompts

- Who fights this weekend, and where can I watch?
- Show the record and last five fights of Oleksandr Usyk.
- What are the current WBC heavyweight rankings?
- Results of last night's boxing cards.
- When is the next fight for Naoya Inoue?

## Tools

boxing_schedule, boxing_results, boxer, bout, next_fight, rankings, search, search_boxers, where_to_watch, fetch.

## License

Extension code: MIT (see LICENSE). Data comes from Boxerbook and is free to read and cite with attribution ("Data: Boxerbook (boxerbook.com)", link the `url` field of each answer); use in apps is by agreement via an API key. Terms: https://boxerbook.com/terms. Data obtained before 2026-11-03 stays under the ODbL.
