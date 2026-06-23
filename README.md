```md
[b][size=xx-large][color=#FF0000]HACKFORUMS / MYBB ADVANCED POSTING GUIDE[/color][/size][/b]

[i][color=#808080]Clean structure model for technical threads, exploit writeups, and research posts[/color][/i]

[hr]

[b][size=x-large][color=#FFA500]OVERVIEW[/color][/size][/b]

This guide defines a stable structure for MyBB / HackForums posts with emphasis on:
[list]
[*]Parser-safe BBCode usage
[*]Technical clarity
[*]Exploit and research documentation formatting
[*]Clean hierarchical layout
[/list]

[hr]

[b][size=x-large][color=#FF0000]THREAD STRUCTURE MODEL[/color][/size][/b]

Recommended order of sections:

[list=1]
[*]Title Block
[*]Abstract
[*]Scope
[*]Methodology
[*]Technical Details
[*]Results
[*]Security Impact
[*]Conclusion
[/list]

[hr]

[b][size=x-large][color=#FFA500]TITLE BLOCK STANDARD[/color][/size][/b]

[code]
[b][size=xx-large]THREAD TITLE[/size][/b]

[i][color=#808080]Author: Handle | Date: YYYY-MM | Classification: Public / Research[/color][/i]
[/code]

Rule:
Keep all styling inside the title block only.

[hr]

[b][size=x-large][color=#FFA500]FORMATTING RULESET[/color][/size][/b]

Color semantics:

[code]
#FF0000 = critical / exploit / risk
#FFA500 = structure headers
#0088FF = technical references
#808080 = metadata
[/code]

Rules:
[list]
[*]Do not mix multiple semantic colors in same line
[*]Do not color entire paragraphs
[*]Use color only for headers or labels
[/list]

[hr]

[b][size=x-large][color=#FF0000]TECHNICAL CONTENT BLOCKS[/color][/size][/b]

All technical material must be isolated.

[b]Standard code block:[/b]

[code]
function test(input) {
    return input;
}
[/code]

[b]Language blocks:[/b]

[php]<?php echo "test"; ?>[/php]
[js]console.log("test");[/js]
[python]print("test")[/python]

Rule:
Do not mix BBCode formatting inside code blocks.

[hr]

[b][size=x-large][color=#FFA500]EXPLOIT / RESEARCH TEMPLATE[/color][/size][/b]

[code]
[b][size=x-large]TITLE[/size][/b]

[i]Short description[/i]

[hr]

[b]ABSTRACT[/b]
High level explanation of behavior or vulnerability.

[hr]

[b]SCOPE[/b]
[list]
[*]Target system
[*]Version range
[*]Environment
[/list]

[hr]

[b]METHODOLOGY[/b]

[list=1]
[*]Recon
[*]Analysis
[*]Reproduction
[/list]

[hr]

[b]TECHNICAL BREAKDOWN[/b]

[code]
function vulnerable(input):
    return exec(input)
[/code]

[hr]

[b]RESULTS[/b]
Observed behavior output or system response.

[hr]

[b][color=#FF0000]SECURITY IMPACT[/color][/b]
Risk classification and potential exploitation impact.

[hr]

[b]CONCLUSION[/b]
Summary of findings and final notes.
[/code]

[hr]

[b][size=x-large][color=#FFA500]LIST USAGE RULES[/color][/size][/b]

Correct usage:

[code]
[list]
[*]Single atomic point
[*]Single atomic point
[*]Single atomic point
[/list]
[/code]

Rules:
[list]
[*]One idea per bullet
[*]No paragraphs inside list items
[*]No nested complexity beyond 2 levels
[/list]

[hr]

[b][size=x-large][color=#FFA500]MEDIA USAGE[/color][/size][/b]

Images:

[code]
[img]https://example.com/image.jpg[/img]
[/code]

Resized images:

[code]
[img=600x300]https://example.com/image.jpg[/img]
[/code]

Video:

[code]
[youtube]VIDEO_ID[/youtube]
[/code]

Rules:
[list]
[*]Media must support technical content
[*]Do not use media for decoration
[*]Keep media isolated in sections
[/list]

[hr]

[b][size=x-large][color=#FFA500]LAYOUT STABILITY RULES[/color][/size][/b]

[list]
[*]Do not overuse [hr]
[*]Do not nest BBCode inside [code]
[*]Keep hierarchy linear
[*]Separate explanation from implementation
[*]Avoid redundant styling
[/list]

[hr]

[color=#808080][size=small]MyBB Advanced Posting System 2026 Stable Build[/size][/color]
```
