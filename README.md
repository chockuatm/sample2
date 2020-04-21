<app-header></app-header>
<div class="page-wrapper mar-top-20 api_cntc">
   <div class="tocify-wrapper">
      <ul class="search-results"></ul>
      <div id="toc" class="tocify">
        <!--  <ul id="tocify-header0" class="tocify-header">
            <li class="tocify-item" data-unique="introduction" style="cursor: pointer;" (click)="shwcontent('introduction')" id="introduction"><a class="section-header">Introduction</a></li>
         </ul>
          -->

         <ul id="tocify-header1" class="tocify-header">
            <li class="tocify-item" data-unique="general-ticker-price"  id="general-ticker-price"><a>Ticker Api</a></li>
         </ul>

      </div>
   </div>

   <div class="content_body">
      <div class="dark-box"></div>
      <div class="content">

          <div id="content_introduction" class="showcontent">
            <div name="introduction" data-unique="introduction"></div>
            <h1 id="introduction" class="section-header">Introduction</h1>
            <blockquote>
              Introduction
            </blockquote>
            <pre class="highlight plaintext"><code>{{frontend}}</code></pre>
            <p>The Trackonbtc API Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. 
            </p>
          </div>

         <div id="content_general-ticker-price" class="showcontent">
         <div name="general-ticker-price" data-unique="general-ticker-price"></div>
         <h2 id="general-ticker-price">Ticker Price</h2>
         <blockquote>
            <p>Ticker Price</p>
         </blockquote>
          <pre class="highlight node"><p><code class="highlight">{{backendHost}}api/tickerprice</code></p>
            </pre>
          <pre class="highlight json"><p><code class="highlight">{{all_pair}}</code></p>
            </pre>
         <h3 id="http-request">HTTP Request</h3>
         <p><code class="prettyprint">GET : {{backendHost}}api/tickerprice</code></p>
         <h3 id="json-response-payload">JSON Response Payload</h3>
         <table>
            <thead>
               <tr>
                  <th>Field Name</th>
                   <th>Type</th>
                   <th>Description</th>
                   <th>Units</th>
               </tr>
            </thead>
            <tbody>
               <tr>
                   <td>NULL</td>
                  <td>NULL</td>
                  <td>NULL</td>
                  <td>NULL</td>
               </tr>
            </tbody>
         </table>

         <h3 id="http-request">HTTP Request</h3>
          <blockquote>
            <p>Ticker Price Variations</p>
         </blockquote>
          <pre class="highlight node"><p><code class="highlight">{{backendHost}}api/tickerprice?pair=BTC/INR</code></p>
            </pre>
          <pre class="highlight json"><p><code class="highlight">{{pair_price}}</code></p>
            </pre>
         <p><code class="prettyprint">GET : {{backendHost}}api/tickerprice?pair=BTC/INR</code></p>
         <h3 id="json-response-payload">JSON Response Payload</h3>
         <table>
            <thead>
               <tr>
                  <th>Field Name</th>
                   <th>Type</th>
                   <th>Description</th>
                   <th>Units</th>
               </tr>
            </thead>
            <tbody>
               <tr>
                <td>Pair</td>
                <td>String</td>
                <td>Trade pair (BTC/INR)</td>
                <td>Major</td>
               </tr>
            </tbody>
         </table>
         </div>

      </div>
   </div>
</div>
<!-- Footer -->
<app-footer></app-footer>
