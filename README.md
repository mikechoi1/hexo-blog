1. need to install hexo cli to use commands:
	npm install hexo-cli -g

2. To find all the posts, go to source/_posts
3. To make a new post, on terminal in the project directory use the command:
hexo new [name-of-post-with-no-space]

4. The new post should show up under the "_posts" directory along with all the previous posts

5. To change the brand icon on the top left of the navbar (currently it's "Jordan's Blog"), a new picture can be placed in [project-name]/themes/news/source/images/ and replace the logo.png with the new picture with the same name

6. To change favicon.png, replace already existing favicon.png in [project-name]/public/ with desired icon of same name

7. To change the ABOUT page, go to [proect-name]/source/about

8. To run on local server run:
	hexo server

9. Change config.yml file in root directory for meta data and deploying settings
This link is helpful as a step by step guide to upload to github pages:
https://zirho.github.io/2016/06/04/hexo/