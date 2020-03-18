<h2>salekin01.github.io</h2> 

<p>GitHub Pages is a static site hosting service that takes HTML, CSS, and JavaScript files straight from a repository on GitHub, optionally runs the files through a build process, and publishes a website. </p>

<h3>How to publish</h3>
  <ol>
    <li>Create a repository owned by your user account that's named <code>&lt;user&gt;.github.io</code></li>
    <li>Now create a folder named <code>&lt;user&gt;.github.io</code> in your local directory</li>
    <li>Copy your project files (css or html or javascript) into that folder. For examples:</li>
     <img src="images/project_files.jpg" width=50% height=50%>
    <li>Open <B>Git Bash</B> in that same folder</li>
    <li>Now type the bellow git commands in <B>Git Bash</B> to push the local files to git repository</li>
       <ol>
        <li>git init</li>
        <li>git add .</li>
        <li>git commit -m “initial commit"</li>
        <li>git remote add origin &lt;Github repository url&gt;</li>
        <li>git push origin master</li>
      </ol>
    <li>Now browse your static web site using <code>&lt;user&gt;.github.io</code></li>
  </ol>
 
