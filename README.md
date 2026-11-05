# PMNote for Gemini CLI

PMNote helps readers find public articles, podcasts and resources about game project management, career development and AI tools. Resources are mainly in Chinese.

```sh
gemini extensions install https://github.com/chenhao233/pmnote-gemini-extension
```

Example: 查找 PMNote 关于游戏项目版本排期的文章，整理常见风险并附上来源。

Python 3.9+ and internet access are needed for the optional reader. It reads pmnote.ai and the site's public Supabase endpoint for interview search; the agent may open linked public sources. No private API key is required. See the included Skill for usage and license terms. External linked works retain their own rights.

## Compatible agent plugins

The portable `plugin.json` also allows compatible agent clients to discover `skills/pmnote`. The package's license permits distribution through the specified markets; linked articles and external works remain under their own terms.

The public interview reader retrieves the website's anonymous connection details and sends interview search terms to the site's Supabase endpoint. Standard network requests reveal request metadata to their destinations. The [PMNote website privacy policy](https://pmnote.ai/privacy/) covers the website and iOS app; [support](https://pmnote.ai/support/) is available for questions.
