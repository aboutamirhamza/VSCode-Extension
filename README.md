<h1>VS Code Extensions</h1>
<br>
<h2>HTML & CSS Extensions:</h2>
<br>

1. Auto Rename Tag (Jun Han) - Automatically renames HTML or XML tags when you modify the opening or closing tag.

2. Auto Close Tag (Jun Han) - Automatically add HTML/XML close tag.

3. SVG Preview (Simon Siefke) - Provides a live preview of SVG files directly in the editor.

4. HTML CSS Support (ecmel) - Provides enhanced CSS support within HTML files. It offers intelligent suggestions and auto-completion for CSS properties.

5. IntelliSense for CSS class names (Zignd) - Provides intelligent suggestions and auto-completion for CSS class names.

6. CSS Peek (Pranay Prakash) - It is a powerful extension that enhances CSS development by allowing you to peek into the associated CSS styles directly from HTML or JavaScript code.

7. Stylelint (Stylelint) - Official Stylelint extension for Visual Studio Code.

8. Tailwind CSS IntelliSense (Tailwind Labs) - Intelligent Tailwind CSS tooling for VS Code.

9. HTML Boilerplate (sidthesloth)

<h2>JavaScript Extensions:</h2>
<br>

10. JavaScript (ES6) Code Snippets (charalampos karypidis) - Extension offers a collection of handy code snippets that can save you time and effort while writing JavaScript code.

11. ESLint (Microsoft) - It is a widely adopted linter that helps you catch errors, enforce coding standards, and improve code quality in JavaScript and TypeScript.

12. Prettier (Prettier) - Code formatter that enforces consistent code style across your projects.

<h2>PHP Extensions:</h2>
<br>

13. PHP Intelephense

14. PHP DocBlocker

15. PHP Namespace Resolver

<h2>BOOST UP EDITOR:</h2>
<br>

16. Live Server (Ritwick Dey) - Allows you to create a local development server with live reloading.

17. Code Spell Checker (Street Side Software) - Spelling Checker for Visual Studio Code.

18. CodeSnap (adpyke) - Simplifies the process of taking code screenshots.

19. vscode-icons (VSCode Icons Team) - Brings a touch of visual brilliance to your coding workspace by replacing the default file icons.

20. GitLens (GitKraken) - It is a powerful extension that integrates Git capabilities directly into your editor.

21. Code Runner (Jun Han) - Provides a convenient way to quickly run code snippets or entire files in various programming languages from within Visual Studio Code.
    
22. GitHub Copilot (GitHub github.com) - This extension is enabled globally. Get Code Suggestions in real-time, right in your IDE
    
23. One Dark Pro (binaryify) - Atom's iconic One Dark theme for Visual Studio Code. Atom's iconic One Dark theme, and one of the most installed themes for VS Code!
    
24. Learn with Sumit Theme (Learn with Sumit) - Official VS Code theme of Learn with Sumit! This extension is enabled globally.

25. Error Lens (Alexander) - Improve highlighting of errors, warnings and other language diagnostics.

26. Material Icon Theme (Philipp Kief) - Material Design Icons for Visual Studio Code.

27. Peacock (John Papa) - Subtly change the workspace color of your workspace. Ideal when you have multiple VS Code instances and you want to quickly identify which is which.

28. Auto-Open Markdown Preview (hnw) - Open Markdown preview automatically when opening a Markdown file.

29. Markdown All in One (Yu Zhang) - All you need to write Markdown (keyboard shortcuts, table of contents, auto preview and more).

30. IntelliCode (Microsoft) - AI-assisted development.

31. Git History (Don Jayamanne) - View git log, file history, compare branches or commits.

32. Git Graph (mhutchie) - View a Git Graph of your repository, and perform Git actions from the graph.

33. vscode-pets (Anthony Shaw) - Pets for your VS Code.

34. Tabnine: AI Autocomplete & Chat for Javascript, Python, Typescript, PHP, Go, Java & more (TabNine) - AI coding assistant with AI code completions and AI code chat right in the IDE, helping developers by generating code, writing unit tests and documentation, explaining legacy code, and much more. Tabnine supports all major languages including JavaScript, Python, Java, Typescript c/c++ and more.



<h2>PHP Path SHortcut System:</h2>
<br>


Vscode::Software::Menubar::-> File -> Preferences-> Configure User Snippets -> html.json(HTML) -> Enter

        "php": {
		"prefix": "php",
		"body": [
			"<?php ?>"
		],
		"description": "PHP Tag"
	}


	"phpecho": {
		"prefix": "phpecho",
		"body": [
			"<?php echo ''; ?>"
		],
		"description": "PHP echo"
	}

	"phpinclude": {
		"prefix": "phpinclude",
		"body": [
			"<?php include ''; ?>"
		],
		"description": "PHP include"
	}

	"phprequire_once": {
		"prefix": "phprequire_once",
		"body": [
			"<?php require_once ''; ?>"
		],
		"description": "PHP require_once"
	}

	"phprequire": {
		"prefix": "phprequire",
		"body": [
			"<?php require ''; ?>"
		],
		"description": "PHP require"
	}
