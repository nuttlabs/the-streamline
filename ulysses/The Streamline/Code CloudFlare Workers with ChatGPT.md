
ChatGPT’s ability to write proper code is one of its most valuable immediate benefits. It’s a concrete example of the AI’s profound sophistication and utility. In one of my favorite examples, I reluctantly asked ChatGPT to program a Cloudflare Worker—and it _nailed_ it.

[Cloudflare Workers](https://workers.cloudflare.com/) help developers at every level bolster their web apps. As an intermediate front-end developer, I use them to emulate server-side functions. Most often, I redirect HTTP requests based on various conditions.

When I migrated the [Notion VIP](https://notion.vip) affiliate program to a new platform, I needed to redirect each affiliate’s URL. A Cloudflare Worker was the obvious solution, but for me, writing and refining the code would have taken hours. So skeptically, I provided ChatGPT with my needs, written naturally and formatted as a bullet list: 

```
You're a computer programmer. Write a Cloudflare Worker that does this:

- Find a substring in the URL between "a-to-z/" and ("/" or the end)
- Assign that substring to the variable "token"
- If "token" is "sexok4PB4bgmCGak" assign "toolfinder" to the variable "key"
- Redirect the request to "https://notion.vip/a-to-z?via=" + "key"
```

The response astonished me as much as any other from ChatGPT. It included clean code with helpful comments, followed by installation instructions. 