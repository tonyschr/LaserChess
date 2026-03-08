# LaserChess

Starting a new project with Claude AI to bootstrap. This is an AI learning excercise.

Brief log:

Authored GAME_OVERVIEW.md and set Claude Sonnet 4.6 to work.

Token overflow. Set environment variable: CLAUDE_CODE_MAX_OUTPUT_TOKENS=64000

The retry took about 20 minutes and succeeded. It was ugly but kind-of worked! That's the initial commit.

A few days later, taking a look at the code and didn't like how the SVG was being authored programmatically. Asked Claude "One change I'd like to make is how the pieces are drawn. Instead of having drawStomper, etc. programmatically create and append SVG nodes, these should be HTML5 <svg> elements that a designer can author in a tool such as InkScape. The orientation is by default facing up (0 degrees) and the rotation will be applied programmatically."

"The use of the double dashes (--pf, --ps) is breaking tooling. Can you change the styles to avoid the double dash (--)?"
