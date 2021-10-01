<h1>Munch</h1>
<p>Pizza ordering project</p>

![alt text](https://github.com/deggion/Munch/blob/readme/app/images/src/header-munch.jpg?raw=true)

<h2>How to start a project</h2>

<p>Clone into the current folder and remove all unnecessary (one command):</p>

<pre>git clone https://github.com/deggion/Munch.git</pre>

<ol>
	<li>Clone or <a href="https://github.com/deggion/Munch/archive/refs/heads/master.zip">Download</a> <strong>Munch</strong> from GitHub</li>
	<li>Install Node Modules: <pre>npm i</pre></li>
	<li>Run: <strong>gulp</strong> <pre>gulp</pre></li>
</ol>

<h2>Main Gulpfile.js options:</h2>

<ul>
	<li><strong>preprocessor</strong>: Optional preprocessor (sass, less, styl). 'sass' also work with the Scss syntax in "styles/sass/blocks/" import folder</li>
	<li><strong>fileswatch</strong>: List of files extensions for watching & hard reload</li>
</ul>

<h2>Main Gulp tasks:</h2>

<ul>
	<li><strong>gulp</strong>: run default gulp task (scripts, images, styles, browsersync, startwatch)</li>
	<li><strong>scripts, styles, images, assets</strong>: build assets (css, js, images or all)</li>
	<li><strong>deploy</strong>: project deployment via <strong>RSYNC</strong></li>
	<li><strong>build</strong>: project build</li>
</ul>