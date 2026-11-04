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

Extension code: MIT (see LICENSE). Data comes from Boxerbook; terms at https://boxerbook.com/terms. Please cite the `url` fields and credit Boxerbook.
