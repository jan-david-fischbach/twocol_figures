# Example of a two column paper
+++ { "part": "abstract" } 
This is the abstract of the two-column paper. It provides a brief summary of the content and main findings of the paper. It is not relevant tu the issue presented here.
+++

## Introduction
This is an example of a two-column paper using Markdown syntax. The content will be organized into two columns for better readability and presentation. It is challenging to format single column figures correctly in myst markdown: There is two choices for the width paramter (e.g. 50% and 100%), none of which leads to the desired behavior:

::: {note} Desired Behavior
**Online Version:**
A single column figure is generally rather narrow. As such it should be centered within the column and be approximately 50% of the column width.

**Print Version:**
A single column figure should span the full column it belongs to.
:::

Depending on the width parameter used either one or the other version is achieved, but not both at the same time:

```{figure} ./images/narrow_figure.png
:width: 50%
:name: fig:narrow_figure_narrow  

This figure uses a width of 50%. It looks good in the online version, but is too narrow in the print version. All figures were generated using ChatGPT-5.
```

```{figure} ./images/narrow_figure.png
:width: 100%
:name: fig:narrow_figure_wide

This figure uses a width of 100%. It looks good in the print version, but is too wide in the online version.
```

## Lorem Ipsum


Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur luctus lorem in ligula hendrerit, nec mattis quam ultricies. Suspendisse interdum orci pretium rutrum pellentesque. Phasellus lacinia justo at efficitur hendrerit. Aenean ligula sem, volutpat quis arcu et, scelerisque sollicitudin purus. Sed non congue leo. Sed ultricies nisi at mauris lobortis, quis maximus justo sagittis. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Sed mattis libero sed dui pulvinar dictum. In vitae urna a augue elementum fermentum. Nulla quis mauris lobortis justo pharetra faucibus in sed arcu. Vestibulum non malesuada ante. Maecenas accumsan placerat lobortis. Donec maximus, nisi ac finibus pellentesque, dolor lorem feugiat neque, porttitor tincidunt ipsum enim eu erat.

Fusce viverra porttitor ornare. Duis sit amet metus in arcu pulvinar feugiat. Suspendisse vitae enim faucibus, laoreet lorem non, vulputate dolor. In iaculis vestibulum turpis non accumsan. Etiam vel venenatis magna. Vivamus in sollicitudin urna. In blandit nisl odio, eu consequat dui maximus in. Nunc at sagittis lectus. Quisque lacinia nisl id nibh mattis tempus. Nam quis tristique risus.

Suspendisse justo mauris, ornare quis pharetra id, commodo quis sem. Ut elit diam, porta non tellus id, scelerisque fringilla sem. Nullam ultrices nisl non erat ultricies laoreet. Phasellus iaculis bibendum nibh a imperdiet. Phasellus tempus, felis vitae finibus posuere, risus lacus scelerisque metus, eget euismod libero leo sit amet sem. Maecenas mattis mattis urna, et placerat lacus finibus in. Etiam sem velit, bibendum a quam nec, sollicitudin commodo odio. In sodales arcu eget erat sagittis, eu porta risus blandit. Fusce eget odio sit amet lorem mattis luctus imperdiet quis enim. Vestibulum lacus mauris, vehicula quis turpis hendrerit, vestibulum tempus velit. Aliquam justo tellus, ultricies aliquet enim eget, fermentum pulvinar erat. Aliquam erat volutpat. Nullam vitae diam orci. Sed ac semper dui.

Aenean arcu augue, fringilla in diam et, maximus malesuada metus. Quisque auctor pharetra tortor vel maximus. Nullam tincidunt eros a semper bibendum. Mauris ultrices metus tellus, at hendrerit arcu mollis eu. Suspendisse eu sodales tellus. Praesent pulvinar mattis sem, a iaculis risus pulvinar ut. Proin eu lectus ac metus vestibulum euismod quis eu quam. Sed vulputate sem vitae varius cursus. Curabitur mattis lobortis sapien eget consequat. Integer euismod pellentesque nisl. Donec erat velit, posuere sed mauris id, luctus lacinia felis. Integer sed sapien ut tortor porta blandit a vel tortor.

Praesent nunc felis, elementum vel pulvinar id, aliquam et nulla. Nullam suscipit, felis vel pretium dapibus, orci dolor varius orci, a iaculis mi massa vel ex. Donec nec sagittis leo. Nunc libero nulla, volutpat id maximus quis, interdum a ante. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. In fringilla id purus vitae eleifend. Praesent et dignissim tellus. Mauris imperdiet maximus auctor. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Etiam finibus pharetra congue. Aliquam sollicitudin vitae ipsum ac pretium. Nullam feugiat et libero sit amet faucibus. 
