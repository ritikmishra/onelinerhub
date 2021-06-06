# oneliner:hub
A lib of micro code pieces, well explained and mostly single-line solutions @ [onelinerhub.com](https://onelinerhub.com/)

![oneliner:hub example](/example.png)

## Help by contributing
Create a pull request with new code files or edited versions of current files.

## Principles
- Micro solutions are ment to solve specific issue in **modern** versions of technologies (browsers, compilers, databases, etc.)
- Solution should be as short and simple as possible
- Solution should be explained by components (variables, functions, operations, etc.)
- Image illustrations are welcome

## Code file micro-format
- Each code file should be placed in it's main technology folder (e.g. "php", "bash", etc).
- File should have short but understandable naming in underscore format (e.g. "redirect_header.md")
- Extension is always ".md", so all the markdown works
- File must include title (```"# title"```) as the first line, without technology (it is automatically added in UI: "{title} in {technology}")
- File must include actual code snippet in the [highlighted code](https://guides.github.com/features/mastering-markdown/) block
- File should also include code parts description, so it's well explained (example in [template](/template.md))
- File can also include group definition to link similar solution (e.g. different date formats or string comparison methods)
- You can upload PNG file with the same file name as the code file and it will automatically be rendered in UI

Use [this template](/template.md) for creating new code pieces.
