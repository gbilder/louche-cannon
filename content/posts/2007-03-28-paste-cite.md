---
title: 'Paste & Cite'
author: gbilder
type: post
date: 2007-03-28T06:39:59+00:00
url: /blog/2007/03/paste-cite/
draft: false
categories:
  - Technology

---
I was recently asked by somebody to speculate about generalizable application features that might help researchers in their work. I responded to them directly, but thought it might be worth repeating part of my response here.

Since the early 1990s I&#8217;ve wished that the OS (any OS) would support a &#8220;Paste & Cite&#8221; feature and, now that I&#8217;m [involved][1] with [CrossRef][2] and its linking and (nascent) plagiarism detection initiatives, I am even more convinced that such a feature would be immensely valuable to anybody who does research. The basic idea behind the feature would be that the clipboard would also copy &#8220;provenance&#8221; information whenever somebody chose to copy something. Then, when the user decided to paste the content someplace else, it would offer an optional &#8220;Past & Cite&#8221; menu item.

This is similar to [Ray Ozzie&#8217;s][3] concept of the [Live Clipboard][4]&#8211; but I think it is simpler and with a different emphasis. The goal here is not to copy structured data around- it is to keep track of where it came from in the first place. In the simplest case, &#8220;Paste & Cite&#8221; would just paste in a URI pointing to the origin of the content (e.g. a local file, a file on an SMB share or a web page). This alone would help immensely with those situations where one &#8220;loses track&#8221; of where quoted text, copied pictures, etc. came from. Apparently a large number of semi- plagiarism cases stem from authors inadvertently losing track of the provenance of material that they copy and paste (with the best intentions of citing the material). In more sophisticated scenarios, the system would be opportunistic and &#8220;Paste & Cite&#8221; might make use of Dublin Core + PRISM metadata imbedded in HTML or XMP in PDFs/ Images or ID3 in mp3s, etc. Again the idea would be to give people a simple (possibly even simplistic) way of keeping track of the provenance of something. And of course- if a [DOI][5] were present, the provenance information could make use of it in order to ensure that the URI doesn&#8217;t break.

## Afterword (December, 2017)

- Apple's iBooks has a function like this now.
- I hope, that a proposed new [`cite-as` link relation type](https://tools.ietf.org/id/draft-vandesompel-citeas-00.html) will encourage more applications to provide this functionality with web resources.


 [1]: http://www.crossref.org/01company/pr/press12052006.htm
 [2]: http://www.crossref.org/
 [3]: http://en.wikipedia.org/wiki/Ray_Ozzie
 [4]: http://rayozzie.spaces.live.com/blog/cns!FB3017FBB9B2E142!285.entry
 [5]: http://www.doi.org/index.html
