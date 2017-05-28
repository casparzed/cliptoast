# cliptoast
Cut Copy JavaScript Library

# Setup
First, include the script located on the source folder.<br>
<code>&lt;script src="cliptoast.js"&gt;&lt;/script&gt;</code></br>
Now, you need to instantiate it. This selector corresponds to the trigger:<br>
<code>
&lt;a class="button" href="#"&gt;Copy&lt;/a&gt;
new ClipToast(".button");
</code>

# Usage
<code>
&lt;!-- Target --&gt; <br>
&lt;textarea id="foo"&gt;Duis aute irure dolor in reprehenderit&lt;/textarea&gt; <br>
&lt;!-- Trigger --&gt; <br>
&lt;a class="button" data-cliptoast-action="cut" data-cliptoast-target="#foo"&gt;
Cut to clipboard
&lt;/a&gt;
</code>

# A lot more things to come.
