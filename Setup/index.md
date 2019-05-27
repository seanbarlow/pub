## Setting up a blog on GitHub Pages and customizing the theme

I have not done any blogging in the past. I decided to look into what capabilities [GitHub](https://www.github.com) provides. It apperas [GitHub](https://www.github.com) quite a robust blogging platform. I have been goin gover the docs and different compoenents and have been very impressed.

I have already

1. Setup a GitHub reporository for the blog
2. Configured GitHub pages for the repository.
3. Selecteda theme for the blog

Next steps

1. Figure out how to customize the theme

### Customizing the styles
To customie the css we are going to need to add a new scss file to our project. The file should be located under assets/css/style.scss.

we are going to add the following to the file.

```
@import "{{ site.theme }}";
```

Basically, we can add any css we want under the import statement.

### Customizing the html

To customize the html we are going to create a new file named default.html. The file should be located under /_Layouts/default.html.

The next thing we are going to so is copy the html from the existing theme. The URL for the theme I was using is https://github.com/pages-themes/architect/blob/master/_layouts/default.html. You can replace architect in the URL with the theme you chose to find the existing html.

