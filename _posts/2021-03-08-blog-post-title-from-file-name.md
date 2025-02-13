---
author: John Doe
facebook_username: john.doe
twitter_username: johndoe
google_username: johndoe
linkedin_username: johndoe
instagram_username: johndoe
github_username: johndoe
tags: template-post 
image: https://user-images.githubusercontent.com/103458862/222838288-b2d963e2-8a96-4206-befb-debf134048e9.jpg
---

## Blog Post Title From First Header

Due to a plugin called `jekyll-titles-from-headings` which is supported by GitHub Pages by default. The above header (in the markdown file) will be automatically used as the pages title.

If the file does not start with a header, then the post title will be derived from the filename.

This is a sample blog post.

---

### This is a header

#### Some PowerShell Code

```powershell
Write-Host "This is a powershell Code block";

# There are many other languages you can use
ForEach ($thing in $things) {
    Write-Output "It highlights it using the GitHub style"
}
```
#### Some Python Code

```python
#!/usr/bin/env python3
from http.server import HTTPServer, SimpleHTTPRequestHandler, test
import sys

class CORSRequestHandler (SimpleHTTPRequestHandler):
    def end_headers (self):
        self.send_header('Access-Control-Allow-Origin', '*')
        SimpleHTTPRequestHandler.end_headers(self)

if __name__ == '__main__':
    test(CORSRequestHandler, HTTPServer, port=int(sys.argv[1]) if len(sys.argv) > 1 else 8000)
```
