# Scraping-Top-Repositories-for-Topics-on-GitHub
This is a Python Script which gets details like repository name, username, stars and repository URLof top repositories in each topic from Github and store them in a CSV file.<br><br>

# Workflow of Project
<ul>
<li>First I scraped <a href="https://github.com/topics">https://github.com/topics</a></li>
<li>Then I got a list of topics.For each topic, I scraped topic title,topic page URL and topic description.</li>
<li>Then for each topic,I scraped the top 25 repositories in the topic from the topic page.</li>
<li>Now for each repository,I grabed the repository name,username,stars and repo URL.</li>
<li>Then for each topic I created a CSV file in the following format.</li>
</ul>
<p>Repo Name,Username,Stars,Repo URL<br>
three.js,mrdoob,69700,https://github.com/mrdoob/three.js<br>
libgdx,libgdx,18300,https://github.com/libgdx/libgdx</p><br>
