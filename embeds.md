---
icon: rocket
order: -2
---

# Embed Configuration

## Embed maker Variables

- **Color (Optional):** `$v{color: [Hex Color Code]}`
- **Title:** `$v{title: Embed Test}`
- **Description:** `$v{description: Embed Test}`
- **Author (Optional):** `$v{author: Embed Test && loti.dev && [Author Image URL]}`
- **Footer (Optional):** `$v{footer: Embed Test && [Footer Image URL]}`
- **Image (Optional):** `$v{image: [Image URL]}`
- **Thumbnail (Optional):** `$v{thumbnail: [Thumbnail Image URL]}`
- **Fields:** `$v{field: [Name] && [Value] && [Inline (if true)]}`

### for variables inside embeds please refer to [this](/variables.md)

![embed example](/static/example.png)
![embed example](/static/example2.png)

## :icon-copy: `;copyembed`

```
;copyembed <messageId>
```

### Description

The `;copyembed` command retrieves the embed code of an message with a embed attachted based on its message ID.

### Parameters

- `<messageId>`: The unique identifier of the message containing the embedded content.

### Usage

To use the `;copyembed` command, follow the syntax provided:

```
;copyembed <messageId>
```

Replace `<messageId>` with the ID of the message you want to retrieve the embedded code from.

### Example

```
;copyembed 123456789012345678
```

This command will retrieve the embed code of the embedded message with the ID `123456789012345678`.

### Notes

- The message ID can be obtained by enabling Developer Mode in Discord then right-clicking on the desired message and clicking copy message id.
- The bot must have access to view the specified message in order to retrieve its embedded content.
