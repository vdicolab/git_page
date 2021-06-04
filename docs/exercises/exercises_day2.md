### My markdown exercise day 2 to do

With plain markdown you can highlight in two ways:

1. *Italic*
2. **Bold**

You can add a link to your favourite [website](https://www.sib.swiss/).
Or add an image from that website (find it at `https://www.sib.swiss/images/banners/banner_research_infrastructure.jpg`):

![](https://www.sib.swiss/images/banners/banner_scientific.jpg)

You can also add a local image (this one is stored in `../assets/images/zoom_icons.png`):

![](../assets/images/zoom_icons.png)

Sharing a code is easy, inline you refer to code like this: `pip install mkdocs`.
But often it's more convenient in a code block, e.g. with shell highlighting:

```sh
FILE=my_genes.csv
cat $FILE | cut -f 1,2 -d ','
```

Or with R highlighting for example:

```r
df <- read.csv('my_genes.csv')
```


![](https://www.sib.swiss/images/sib/4-training/training_header_2018.jpg)


!!! warning
    Do not overcommit the server!

    code:


=== "R"
    Generating a vector of integers:
    ```r
    a <- c(5,4,3,2,1)
    ```
=== "python"
    Generating a list of integers:
    ```python
    a = [5,4,3,2,1]
    ```



Write an e-mail :material-send:, add a pdf :material-file-pdf: and wait :clock1:


[Download the presentation](../assets/pdf/introduction_gh_pages.pdf){: .md-button }


[:fontawesome-solid-file-pdf: Download the presentation](../assets/pdf/introduction_gh_pages.pdf){: .md-button }




<figure>
  <img src="https://www.sib.swiss/images/sib/4-training/training_header_2018.jpg" width="300"/>
</figure>


###test

<figure>
  <img src="https://www.sib.swiss/images/sib/4-training/training_header_2018.jpg" width="100"/>
</figure>


=== "code"
    ```md
    Write an e-mail :material-send:, add a pdf :material-file-pdf: and wait :clock1:
    ```
=== "output"
    Write an e-mail :material-send:, add a pdf :material-file-pdf: and wait :clock1:
    ```
