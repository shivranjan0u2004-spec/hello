# hello
hell no
where is the work?


<img width="2754" height="1080" alt="cay" src="https://github.com/user-attachments/assets/04e9e22c-a9f0-4d0e-9a8c-bef116a6bd0c" />
&lt;!DOCTYPE html&gt;
&lt;html lang=&quot;en&quot;&gt;
&lt;head&gt;
&lt;meta charset=&quot;UTF-8&quot;&gt;
&lt;title&gt;SRS GHEE - Pure &amp; Premium&lt;/title&gt;
&lt;link rel=&quot;stylesheet&quot; href=&quot;style.css&quot;&gt;
&lt;script src=&quot;launch.js&quot; defer&gt;&lt;/script&gt;
&lt;/head&gt;
&lt;body&gt;
&lt;header&gt;
&lt;h1&gt;SRS GHEE&lt;/h1&gt;
&lt;nav&gt;
&lt;a href=&quot;index.php&quot;&gt;Home&lt;/a&gt;
&lt;a href=&quot;product.php&quot;&gt;Product&lt;/a&gt;
&lt;a href=&quot;contact.php&quot;&gt;Contact&lt;/a&gt;
&lt;/nav&gt;
&lt;/header&gt;

&lt;footer&gt;

&lt;p&gt;&amp;copy; &lt;?php echo date(&quot;Y&quot;); ?&gt; SRS GHEE. All rights reserved.&lt;/p&gt;
&lt;/footer&gt;
&lt;/body&gt;
&lt;/html&gt;

&lt;?php include &#39;header.php&#39;; ?&gt;
&lt;main&gt;
&lt;section class=&quot;hero&quot;&gt;
&lt;h2&gt;Launching Soon: SRS GHEE&lt;/h2&gt;
&lt;p&gt;Experience purity in every drop. Made with love in India.&lt;/p&gt;
&lt;div id=&quot;countdown&quot;&gt;&lt;/div&gt;
&lt;/section&gt;
&lt;/main&gt;
&lt;?php include &#39;footer.php&#39;; ?&gt;
&lt;?php include &#39;header.php&#39;; ?&gt;
&lt;main&gt;
&lt;section class=&quot;product&quot;&gt;
&lt;h2&gt;Our Product&lt;/h2&gt;
&lt;p&gt;SRS GHEE is crafted from the finest cow milk, slow-cooked to perfection for
unmatched aroma and taste.&lt;/p&gt;
&lt;ul&gt;
&lt;li&gt;100% Natural &amp; Organic&lt;/li&gt;
&lt;li&gt;No Preservatives&lt;/li&gt;
&lt;li&gt;Rich in Nutrients&lt;/li&gt;
&lt;/ul&gt;
&lt;img src=&quot;ghee.jpg&quot; alt=&quot;SRS GHEE Bottle&quot; style=&quot;max-width:300px;&quot;&gt;
&lt;/section&gt;
&lt;/main&gt;
&lt;?php include &#39;footer.php&#39;; ?&gt;

&lt;?php include &#39;header.php&#39;; ?&gt;
&lt;main&gt;
&lt;section class=&quot;contact&quot;&gt;
&lt;h2&gt;Contact Us&lt;/h2&gt;
&lt;form method=&quot;post&quot; action=&quot;&quot;&gt;
&lt;label&gt;Name:&lt;/label&gt;&lt;br&gt;
&lt;input type=&quot;text&quot; name=&quot;name&quot;&gt;&lt;br&gt;&lt;br&gt;
&lt;label&gt;Email:&lt;/label&gt;&lt;br&gt;
&lt;input type=&quot;email&quot; name=&quot;email&quot;&gt;&lt;br&gt;&lt;br&gt;
&lt;label&gt;Message:&lt;/label&gt;&lt;br&gt;
&lt;textarea name=&quot;message&quot;&gt;&lt;/textarea&gt;&lt;br&gt;&lt;br&gt;
&lt;input type=&quot;submit&quot; value=&quot;Send&quot;&gt;
&lt;/form&gt;
&lt;?php
if ($_SERVER[&quot;REQUEST_METHOD&quot;] == &quot;POST&quot;) {
$name = htmlspecialchars($_POST[&quot;name&quot;]);
echo &quot;&lt;p&gt;Thanks, $name! We&#39;ll be in touch soon.&lt;/p&gt;&quot;;
}
?&gt;
&lt;/section&gt;
&lt;/main&gt;
&lt;?php include &#39;footer.php&#39;; ?&gt;

