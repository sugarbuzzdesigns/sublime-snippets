sublime-snippets
================

Sublime Snippets

**What are Sublime Snippets?**

Snippets are smart templates that will insert text for you, adapting it to their context. You can create a snippet by opening sublime, clicking Tools, and new snippet. A new sublime tab/window will open with the following content.

	<snippet>
	  <content><![CDATA[
	    Hello, ${1:this} is a ${2:snippet}.
	  ]]></content>
	  
	  <!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
	  <!-- <tabTrigger>hello</tabTrigger> -->
	  <!-- Optional: Set a scope to limit where the snippet will trigger -->
	  <!-- <scope>source.python</scope> -->
	</snippet>

All you need to do is replace the code in the CDATA with the code you want to turn into a snippet. Once your code is added, just save it to your user packages in Sublime Text. \\
MAC: /Users/{username}/Library/Application Support/Sublime Text 2/Packages/User \\      
PC: C:Users\{username}\AppData\Roaming\Sublime Text 2\Packages\User 

For additional information on writing snippets, check out the Sublime Text documentation.
http://docs.sublimetext.info/en/latest/
