# Motivations-Collection

A simple html page to place all the motivational quotes and prayers. Later this will be designed properly with a proper backend.

# Contributors



# Purpose of this repo

1. It contains quotes from all over the globe so anyone's free to contribute.

2. Right now the repo contains a single html page, which acts as a collection dump for all the quotes different people have to offer. So it's pretty simple to contribute.

3. Later this will be stylised and converted to a proper website, with a proper hosting and a backend where users will be able to upload their own motivational quotes.

# How to contribute
### Note: Please don't create any issue for contribution. Follow along the next steps for contribution. If any problem arises then only an issue should be created.

1. Fork the repository

2. Clone and Open it in a choice of editor. Then create a branch in which you'll commit.

3. Upload the topic specific image of your favourite quote

4. Copy and paste the below code at the end of the ```index.html``` file

```bash
              <!-- start of [quote name] -->
             <article class="col-12 col-md-6 tm-post">
                    <hr class="tm-hr-primary" />
                    <a href="#" class="effect-lily tm-post-link tm-pt-60">
                        <div class="tm-post-link-inner">
                            <!-- Link the respective image here -->
                            <img src="img/img-01.jpg" alt="Image" class="img-fluid" />
                        </div>
                        <span class="position-absolute tm-new-badge">New</span>
                        <h2 class="tm-pt-30 tm-color-primary tm-post-title">
                            [quote]
                        </h2>
                    </a>
                    <div class="d-flex justify-content-between tm-pt-45">
                        <!-- give genre as motivation for motivation and prayer for prayer -->
                        <span class="tm-color-primary">[Genre]</span>
                        <!-- date format dd/mm/yyyy -->
                        <span class="tm-color-primary">[Date]</span>
                    </div>
                    <hr />
                    <div class="d-flex justify-content-between">
                        <span>by [contributor name]</span>

                        <!-- if no author please provide the word "anonymus" in this section -->
                        <span>said by [author name]</span>
                    </div>
                </article>
                <!-- end of [quote name] -->

```


5. Link the image you uploaded and fill the sections accordingly

6. On completion, in the terminal put the following commands:

```bash
git add .

git commit -m "[quote name] contribution from [contributor name]"

git push origin [branch-name]
```

7. Finally create a pull request.


# Live Page

The site is hosted at: [motivations]

[motivations]: https://mark-42-max.github.io/Motivations-Collection/
