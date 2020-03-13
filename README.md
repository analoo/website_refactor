# Website Refactor Homework Read Me

## Site Picture
![Site](./assets/images/website.png)

## Technologies Used
- HTML - used to create elements
- CSS - styles elements on page
- Git - version control system to track changes to source code
- GitHub - hosts repository that can be deployed in GitHub pages

## Summary

This application generates a webpage for a company called Horiseon. It is a standard webpage which provides some basic information about what the company does.

The task for the coder was to to evaluate code to ensure that it is accessible. Always, the goal is to improve the code base and ss with homework, learning is always the ultimate underlying goals. To improve both accessibility and quality of the code, the following steps were taken:

1) Review the webpage to understand its purpose and organization. I focused on: What are the different elements in the webpage? Are there unique formats? I then created a diagram of the elements identified and matched them back to semantic elements. This diagram ultimately became a guide when rebuilding the page.
2) The rebuilding started with the HTML where I changed divs into semantic elements that made sense. For example: with images, I immediately added alt test and with links, I made sure that they went to the right place.
3) I then started with a new css and started adding stylistic elements such as h1, h2, section. In this process, I found items that were unique and created new ids and then at times found elements that could be applied to a small group and added classes.

At quick glance, the new code is at least 10% smaller than the original. Although the quality of the code and its length are not necessarily correlated, I believe that the reduction in lines of code in this case is an improvement. The additional elements introduce opportunity for error and in this case, the streamlining of the code would make it simpler for another coder to update and review.

##Code Snippet

For example, below are comparisons of the new header section with the original. Rather than having a lot of formatting, the new code is straightforward and functional, trying each word to an anchor in the page that it links to.

```Code snippet
<header>
	<h1>Hori<span id="seo">seo</span>n</h1>
	<a href="#social-media-marketing">Social Media Marketing</a>
	<a href="#online-reputation-management">Online Reputation Management</a>
	<a href="#search-engine-optimization">Search Engine Optimization</a>

</header>
```
The previous code focused added many divs to the code that weren't necessary for styling.

``` 
<div class="header">
<h1>Hori<span class="seo">seo</span>n</h1>
	<div>
		<ul>
			<li>
				<a href="#search-engine-optimization">Search Engine Optimization</a>
			</li>
			<li>
				<a href="#online-reputation-management">Online Reputation Management</a>
			</li>
			<li>
				<a href="#social-media-marketing">Social Media Marketing</a>
			</li>
		</ul>
	</div>
</div>
```

## Author Links
[LinkedIn](https://www.linkedin.com/in/ana-medrano-fernandez/)

[GitHub](https://github.com/analoo)