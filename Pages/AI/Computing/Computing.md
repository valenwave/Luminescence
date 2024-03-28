# Computing

* [Internet](Internet.md)

## Can my other team members on Trello see the lists I collapsed?

No, your other team members on Trello cannot see the lists you collapsed. When you collapse a list in Trello, it only affects your individual view of the board. Other team members will see all lists expanded by default.

Trello currently doesn't have a feature that synchronizes collapsed lists across users. This means any customization you make to your board view, including collapsing lists, is specific to you.

Here's a breakdown of what happens when you collapse a list:

Your View: The list title and cards within it are hidden, minimizing clutter and helping you focus on specific parts of the board.
Teammates' View: Other team members will still see the collapsed list title on the board. Clicking on the collapsed title will expand the list and show all its cards, just like it normally appears.
Workarounds and Alternatives:

While there's no direct way to share collapsed list views, here are some workarounds you and your team can consider:

Filters: Trello offers filters that allow you to hide specific cards based on criteria like labels or members assigned. This can help you focus on relevant information without collapsing entire lists.
Custom Boards: If you have a personal workflow that relies heavily on collapsed lists, you can create a separate board for yourself and keep the main team board with all lists expanded for better collaboration.
Board Sections: Trello's board sections can be a good way to organize lists visually. You can group related lists together and potentially collapse entire sections to reduce clutter while maintaining a shared view for your team.
Communication: Discuss your reasoning for collapsing lists with your team. Maybe there's a way to achieve a similar focus through filtering or using board sections collaboratively.
By exploring these alternatives and fostering open communication with your team, you can find ways to manage your Trello board effectively without impacting the visibility for your colleagues.

## What is code smell?

In computer programming, a code smell is a characteristic in the source code of a program that suggests there might be a deeper problem. It's not a definitive sign of an error, but rather a clue that the code might be difficult to understand, maintain, or modify in the future.

Here are some key points about code smells:

Subjectivity: There's no universally agreed-upon list of code smells, and what one programmer considers a smell another might find acceptable. It can depend on coding style, language, and project requirements.
Indicators, Not Errors: Code smells themselves aren't errors that prevent the program from running. They are indicators that the code might be inefficient, hard to read, or error-prone.
Refactoring Opportunities: Identifying code smells is often the first step towards refactoring, a process of restructuring code to improve its readability, maintainability, and overall quality.
Common Examples of Code Smells:

Long Method: A method (a function within a program) that stretches to hundreds of lines of code is a strong candidate for a code smell. It can be difficult to understand and follow the logic of such a long method.
Large Class: A class (a blueprint for creating objects) that encompasses a vast amount of functionality might be a code smell. Large classes can be hard to manage and might benefit from being broken down into smaller, more focused classes.
Duplicate Code: If you find the same block of code repeated in multiple places, it's a code smell. This suggests redundancy and makes future maintenance more challenging. There might be better ways to organize the code using functions or loops.
Magic Numbers: Using unexplained numeric constants throughout the code can make it cryptic and difficult to understand. It's better to use meaningful variable names or constants with clear definitions.
Benefits of Identifying Code Smells:

Improved Code Quality: By addressing code smells, you can create cleaner, more maintainable code that's easier to understand and modify in the future.
Reduced Errors: Code smells can sometimes lead to bugs or unexpected behavior. Refactoring to address these smells can help reduce the likelihood of errors.
Increased Team Productivity: Well-written code with fewer smells is easier for everyone on the development team to understand and work with. This can lead to increased efficiency and collaboration.
By understanding code smells and how to identify them, programmers can take proactive steps to improve the quality and maintainability of their code.

## What are some examples of code smell?

In the world of programming, code smells are indicators that your code might have underlying issues. They don't necessarily mean your code is broken, but they suggest areas for improvement in terms of readability, maintainability, or efficiency. Here are some examples of common code smells to watch out for:

Bloaters:

Long Method: A method (function) that stretches to hundreds of lines is a prime suspect. Imagine trying to follow the logic of a long and winding story – that's what a long method can be like for other programmers.
Large Class: A class (a blueprint for creating objects) that handles a vast amount of functionality can be a code smell. These behemoths can be cumbersome to manage and might benefit from being broken down into smaller, more focused classes.
Data Clumps: Imagine a group of variables that seem to always appear together throughout your code. This redundancy suggests a potential object or data structure that could be created to encapsulate this data more effectively.
Couplers:

Long Parameter List: A function with an excessive number of parameters (often more than 5 or 6) can be difficult to understand and use. It might be a sign that the function is trying to do too much and could benefit from being broken down into smaller functions with more focused purposes.
Feature Envy: This occurs when a method in one class seems overly interested in the data or functionality of another class. This suggests a potential design issue where responsibilities might be better distributed.
God Class: Similar to a large class, a God Class tries to do everything. It houses a massive amount of functionality and serves as a central point of control for many aspects of the program. This can lead to tight coupling and make the code difficult to maintain.
Complexity Smells:

Switch Statements: While switch statements have their place, excessively complex ones with many cases can become cumbersome to manage and error-prone. Consider using polymorphism or a lookup table for more elegant solutions in some cases.
Nested Control Flow: A deep nesting of if/else statements or loops can make the code hard to follow and reason about. There might be opportunities to refactor the code using different control flow structures or functions to improve readability.
Dispensables:

Dead Code: Code that is no longer used but remains in the codebase is like clutter in your attic. It serves no purpose and can potentially add confusion. Regularly cleaning up dead code improves code maintainability.
Unused Variables: Variables declared but never assigned a value or used in the program are also dispensable. They can indicate planning that never came to fruition or errors in the code.
Remember: Context matters. What might be a code smell in one situation could be perfectly acceptable in another.  The key is to understand the principles behind code smells and use your judgment to identify areas in your code that could benefit from refactoring.  By addressing these smells, you can create cleaner, more maintainable code that will be easier for you and your team to work with in the future.

## What's a good web app for making mind maps with branching bubbles and connecting lines?

Here are some good web apps for making mind maps with branching bubbles and connecting lines:

Free options:

[Coggle](https://coggle.it/):  (Web-based, user-friendly interface, good for beginners and occasional use)
[Miro (Free Plan)](https://miro.com/):  (Web-based, offers mind mapping features along with other collaborative whiteboard tools in the free plan)
[Visme (Free Mind Map Maker)](https://www.mindmup.com/):  (Web-based, offers a mind mapping tool with various shapes and line styles, free plan has limitations)
Paid options:

[MindMeister](https://www.mindmeister.com/): (Web-based, extensive features like collaboration, themes, and integrations, free trial available)
[XMind](https://xmind.app/): (Web-based and desktop versions, powerful features for complex mind maps, free trial available)
[Ayoa](https://www.ayoa.com/): (Web-based, focuses on visual collaboration and mind mapping with clean aesthetics, free trial available)
Choosing the right app depends on your needs:

Frequency of Use: If you need a mind map maker for occasional use, a free option like Coggle might be sufficient.
Complexity of Mind Maps: If you create complex mind maps with many branches and connections, consider paid options like XMind or MindMeister that offer advanced features.
Collaboration Needs: If collaboration is important, choose a web app with real-time editing features like MindMeister or Miro.
Personal Preference: Explore the free trials or demos of paid options to see which interface and feature set works best for you.

## Tell me about Jenni.ai

Jenni.ai is an AI writing assistant specifically designed to help with academic writing tasks. It offers a variety of features to enhance the research and writing process for students, researchers, and academics. Here's a breakdown of what Jenni.ai can do:

Core Features:

Writing Assistance:

Text Editor: Jenni provides a user-friendly text editor with features like autocompletion and grammar suggestions to improve writing efficiency and clarity.
Paraphrasing: The tool can help you rephrase sentences or paragraphs while maintaining the original meaning. This can be useful for avoiding plagiarism and expressing your ideas in different ways.
In-text Citations: Jenni can automatically generate in-text citations in various academic styles like APA, MLA, and Chicago. This saves time and helps ensure proper citation formatting.
Research Assistance:

Research Tools: Jenni allows you to conduct basic research directly within the platform. While it's not a comprehensive search engine, it can help gather relevant sources on your topic.
Source Organization: The tool can help you manage your research sources by creating a bibliography and keeping track of relevant information.
Additional Features:

Plagiarism Checker: Jenni has a built-in plagiarism checker that scans your writing for potential instances of unoriginal content. This helps you identify areas where you might need to paraphrase or cite your sources more effectively.
Style and Tone Suggestions: The tool can analyze your writing and suggest improvements for tone, clarity, and overall style, depending on your academic discipline.
Target Users:

Jenni.ai is primarily aimed at students, researchers, and academics who need help with various aspects of the writing process. It can be beneficial for:

Essay Writing: Students can use Jenni to improve their grammar, paraphrase sentences, and ensure proper citations.
Research Papers: Researchers can leverage the tool's research assistance features and built-in citation management to streamline their workflow.
Academic Writing: Professors and scholars can use Jenni to improve the clarity and style of their writing, as well as check for plagiarism.
It's important to note:

Jenni.ai is a tool to assist with writing, not a replacement for critical thinking and original research. It's crucial to understand your topic and paraphrase or cite sources correctly.
While the plagiarism checker can be helpful, it's not foolproof. Always double-check your citations and ensure your understanding of the material.
Overall, Jenni.ai can be a valuable asset for anyone involved in academic writing by providing features that can save time, improve clarity, and ensure proper citation practices.

## Is there a good tool for archiving 3DS games?

Unfortunately, creating a perfect archive of 3DS games presents some challenges due to the way the system operates. Here's why and what options you might consider:

Challenges of 3DS Game Archiving:

Cartridge-Based System: Unlike some disc-based consoles where you can rip a copy of the game data, 3DS games are stored on cartridges. These cartridges aren't easily readable with standard tools.
Copy Protection: 3DS games have built-in copy protection measures that make direct copying difficult.
Emulation Limitations: While 3DS emulation exists, it's still under development and might not perfectly replicate every game's functionality.
Options for Preserving 3DS Games:

While creating a perfect archive isn't possible, here are some approaches you can consider:

Flashcart with Backups: This method involves acquiring a flashcart, a device that allows unauthorized game loading on the 3DS. You can then use tools to create backups of your original game cartridges onto the flashcart. However, this approach  skirts legality in some regions,  so check the  copyright laws in your area. It's also important to note that using unofficial flashcarts might carry some risk of damaging your console.

Ripping Save Files:  While not a full game archive, you can use homebrew applications (unauthorized software) to extract save files from your 3DS games.  This allows you to potentially preserve your progress  if you plan on using an emulator in the future, but it doesn't capture the entire game.  Similar to flashcarts, homebrew applications exist in a legal gray area, so proceed with caution.

Physical Preservation: The safest and most legal option is to simply  maintain your original 3DS game cartridges  in good condition.  Store them in a cool, dry place and avoid exposure to extreme temperatures or sunlight. This ensures you can still play the games on the original hardware.

Documentation and Videos: Consider creating detailed notes or even video recordings of your gameplay for specific 3DS titles you want to preserve.  This can capture the experience and story of the games even if you can't perfectly archive the software itself.

Important Note:  It's always advisable to check the copyright laws in your region before attempting any emulation or game backups. Downloading copyrighted material without permission can be illegal.

While there's no single perfect solution, these methods can help you  partially archive  your 3DS game collection. Remember, emulation is still an evolving field, so there might be better tools or techniques available in the future.

## Is Angi a good service?

Angi, formerly Angie's List, can be a good service depending on your priorities and the specific contractor you choose through the platform. Here's a breakdown of its pros and cons to help you decide:

Pros:

Large Network of Verified Contractors: Angi boasts a large network of pre-vetted home service professionals across various categories.
Reviews and Ratings: The platform provides customer reviews and ratings for contractors, allowing you to compare and choose based on past experiences.
Background Checks: Angi claims to conduct background checks on contractors, offering some peace of mind. (It's important to note that background checks don't guarantee a perfect contractor.)
Potential for Dispute Resolution: Angi offers a dispute resolution process if you encounter issues with an Angi-connected contractor.
Convenience: Angi provides a one-stop shop to find, compare, and potentially hire contractors, streamlining the process.
Cons:

Quality Can Vary: While Angi vets contractors, the quality of service can still depend on the individual you choose. Reading reviews and checking references is crucial.
Not a Guarantee of Success: Angi doesn't directly employ the contractors. There's still a risk of hiring a bad contractor, so do your due diligence.
Potential for Higher Costs: Some contractors might factor in the cost of Angi's service into their quotes, potentially leading to slightly higher prices. It's wise to compare quotes from Angi contractors with independent ones.
Mixed Reviews: Customer experiences with Angi can vary. While some users find good contractors, others might encounter issues.
Here are some additional things to consider:

Get Multiple Quotes: Don't rely solely on Angi. Get quotes from several contractors, both from Angi and independently, to compare prices and services offered.
Read Reviews Carefully: Read Angi reviews critically, paying attention to details and potential red flags mentioned by past customers.
Do Your Research: Even with Angi's pre-vetting process, research the specific contractor you're considering. Check their license, insurance, and online reviews from other platforms.
Don't Skip Contracts: Always have a written contract with the chosen contractor outlining the scope of work, timeline, and costs to avoid misunderstandings.
Overall, Angi can be a useful tool to find and compare potential contractors, but it's not a guaranteed path to perfect service.  Do your due diligence, compare quotes, and prioritize thorough research before hiring anyone for your home service needs.

## What options do I have for online spreadsheets?

There are many online spreadsheet applications available, each with its own strengths and weaknesses. Here are a few of the most popular options:

Google Sheets:

Google Sheets is a free online spreadsheet application that is part of the Google Docs suite. It offers a familiar spreadsheet interface that is similar to Microsoft Excel. Google Sheets integrates seamlessly with other Google applications, such as Google Drive and Google Docs, making it easy to collaborate on spreadsheets with others.

Microsoft Excel Online:

Microsoft Excel Online is the free web-based version of Microsoft Excel. It offers a subset of the features found in the full desktop version of Excel, but it is still a powerful tool for creating and editing spreadsheets. Excel Online integrates with other Microsoft applications, such as OneDrive and SharePoint, making it a good choice for businesses that already use Microsoft products.

Zoho Sheet:

Zoho Sheet is a free online spreadsheet application that offers a wide range of features, including support for formulas, functions, and pivot tables. Zoho Sheet also includes a number of collaboration features, such as real-time co-editing and chat.

Airtable:

Airtable is a hybrid spreadsheet/database application that allows you to create tables with custom fields and views. Airtable is a good choice for projects that require more than just basic spreadsheet functionality.

Smartsheet:

Smartsheet is a project management application that includes a spreadsheet component. Smartsheet is a good choice for teams that need to collaborate on projects that involve data analysis.
The best online spreadsheet application for you will depend on your specific needs. If you need a free and easy-to-use option, Google Sheets or Microsoft Excel Online are good choices. If you need a more powerful spreadsheet application with a wider range of features, Zoho Sheet or Airtable may be a better option. If you need a spreadsheet application that is part of a larger project management system, Smartsheet may be a good choice.
