<h1 align="center">Code Craft API</h1>

<p>This backend was built to be used on the <a href="https://github.com/soymattheus/Coding-Event-Enrollment">Code Craft</a> page, which is available on my github.</p>

<h3>Main used technologies</h3>

<ul>
<li>Typescript</li>
<li>Fastify</li>
<li>Drizzle</li>
<li>Redis</li>
<li>Postgres</li>
<li>Zod</li>
</ul>

<h3>Swagger Image</h3>
<p align="center">
<img loading="lazy" src="./github/images/swagger.png"/>
</p>

<h3>To run the project locally follow these steps</h3>
<ol>
<li>Clone the project:</li>
<p>git clone https://github.com/soymattheus/Coding-Event-Enrollment-Api</p>

<li>Enter the cloned project folder</li>

<li>Install required packges:</li>
<p>npm install</p>

<li>Run this command to start databases in Docker</li>
<p>docker compose up -d</p>

<li>Execute this command to create the database DDl</li>
<p>npx drizzle-kit generate</p>

<li>Execute this command to create the database table</li>
<p>npx drizzle-kit migrate</p>

<li>Run the project locally:</li>
<p>npm run dev</p>
</ol>

<h3>To run prod version, follow these steps:</h3>
<ol>
<li>Run the build command:</li>
<p>npm run build</p>

<li>Run the prod project version</li>
<p>npm run prod</p>
</ol>

<p>I hope you like this little project.</p>
<p>If you have any difficulties, you can send me a message via <a href="https://www.linkedin.com/in/mattheusdev/" target="_blank">linkedIn</a>.</p>
<p>
If you have ideas, contributions or would like to give any constructive criticism, feel free to message me via <a href="https://www.linkedin.com/in/mattheusdev/" target="_blank">linkedIn</a>. Any contribution will be welcome.</p>