# Slide Show (S9) with Shower template docker container

- [rafagc/s9-shower docker container](https://hub.docker.com/r/rafagc/s9-shower)

- [Slide Show (S9) Guide (Book Edition)](https://slideshow-s9.github.io/)

- [Shower (Ribbon, Material) - Slide Show (S9) Template Pack](https://github.com/slideshow-templates/slideshow-shower)

## Example using Material Theme 

[![first slide screenshot](oop.png)](https://rafaies.github.io/s9-shower/generated-slides/oop/index.html)

[Structured Programming vs. Object Oriented Programming](https://rafaies.github.io/s9-shower/generated-slides/oop/index.html "Slide presentation using Shower template with Material theme")

From directory where the markdown file is (oop.md):

```
$ docker run -v $(pwd):/workspace -e INPUT=oop.md --rm rafagc/s9-shower
```
Some CSS changes have been made manually. Compare the generated file [oop.html](generated-slides/oop/mark.html) with the modified file [index.html](generated-slides/oop/mark.html)

For example: class="cover" for background images and class="question".




