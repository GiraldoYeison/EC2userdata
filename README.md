# EC2userdata
Creating an AWS EC2 instance with user data / Launching EC2 Instances and test user data


<div><b>Creation Date:</b> October 18, 2023</div>
<div><b>Created By:</b> Yeison Giraldo</div>

<div style="height: 24px">&#8203;</div>
<hr />
<div style="height: 24px">&#8203;</div>


<div><h3>1. Click on Launch instances</h3>
<p>Click on Launch instances</p>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/09e91603-9054-4011-befe-8bc337ca2118/2831f886-70c2-4be9-b8b7-03ebe37c5a9d.png?fm=png&crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.5000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=1053&mark-y=4&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTMlMkNGRjc0NDImdz0xMTMmaD0yNiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Launch instances" />
</div>

<div><h3>2. Type "myWebServer"</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/fb2a8902-0841-4f08-bfa9-8d62531b70ce/7cedaddc-20aa-4961-9b2c-c18285fee239.png?fm=png&crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.5000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=92&mark-y=262&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTMlMkNGRjc0NDImdz01MzQmaD0zOCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Type &quot;myWebServer&quot;" />
</div>

<div><h3>3. Click on Amazon Linux</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/143cbece-1cdb-4a5a-9479-d1db90b4899b/e1d06a43-19da-4fc0-a995-7fcfb3017f98.png?fm=png&crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.5000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=97&mark-y=225&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTMlMkNGRjc0NDImdz05NiZoPTEyOSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Amazon Linux" />
</div>

<div><h3>4. Click on t2.micro…</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/db051b26-2073-41b9-8ff4-f99919ec0619/8fe839e6-833e-43fa-8a7a-c66003f98e75.png?fm=png&crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.5000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=91&mark-y=480&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTMlMkNGRjc0NDImdz01MjAmaD0xMTQmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on t2.micro…" />
</div>

<div><h3>5. If you have a Key pair already on AWS you can use it or create a new one</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/24e4f84d-f3a6-4bd0-8167-3f089a8ff531/9d90b227-d2c2-40d5-ad1c-38136b72b136.png?fm=png&crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.5000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=92&mark-y=417&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTMlMkNGRjc0NDImdz01MjAmaD0zOCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="If you have a Key pair already on AWS you can use it or create a new one" />
</div>

<div><h3>6. Click on Network settings Info…</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/2c6af974-ef57-45bc-bf11-4bd3b2d41f5d/354561ad-17b2-481c-a365-5496a324809b.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2860&fp-y=0.4845&fp-z=1.1974&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=84&mark-y=78&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02NTMmaD01MDcmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Network settings Info…" />
</div>

<div><h3>7. Click on Edit for network options</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/416e6527-147b-4ec1-a271-f63141ca480f/8b9d5a68-6d09-406f-aa58-057e986fcd06.png?fm=png&crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.5000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=728&mark-y=39&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTMlMkNGRjc0NDImdz03MyZoPTM4JmZpdD1jcm9wJmNvcm5lci1yYWRpdXM9MTA%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Edit for network options" />
</div>

<div><h3>8. Click on Firewall (security groups) to create a new one or select another SG</h3>
<p>make sure you select the correct VPC and Subnet for your EC2</p>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/2f8ae19d-68d0-46e4-aa4c-731fcac43e8d/ffdc9480-5226-4837-b512-4a6b22627365.png?fm=png&crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.5000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=70&mark-y=325&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTMlMkNGRjc0NDImdz00MDcmaD01MCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Firewall (security groups) to create a new one or select another SG" />
</div>

<div><h3>9. We will select a SG that was already made</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/3cf32e6a-6420-4753-9123-32c985ccfc93/0ca7b957-4555-409f-b441-fba4dea1105b.png?fm=png&crop=focalpoint&fit=crop&fp-x=0.3236&fp-y=0.2168&fp-z=2.1289&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=383&mark-y=265&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz00MzQmaD04MSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="We will select a SG that was already made" />
</div>

<div><h3>10. for EBS keep the default or change it to whatever size you need</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/85a90383-12dd-4614-9f37-55407a6ce9e7/9d7ab062-ddad-471d-a04d-6bb5871b1f5a.png?fm=png&crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.5000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=92&mark-y=652&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTMlMkNGRjc0NDImdz0yMzAmaD0zOCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="for EBS keep the default or change it to whatever size you need" />
</div>

<div><h3>11. Click on Advanced details Info</h3>
<p>This is where we will inject the user data to the EC2 when it first boots up</p>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/26f0f648-cefa-41c5-a2cc-78f1ae1e0154/7d75306b-2388-4f1b-849f-a1e700e6123f.png?fm=png&crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.5000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=73&mark-y=693&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTMlMkNGRjc0NDImdz03NDkmaD02OSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Advanced details Info" />
</div>

<div><h3>12. Right click on User data - </h3>
<p>Paste the Script for the EC2 to run when it boots</p><p>Click on "launch instance"</p>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/c267c2bb-6e1a-4946-9e27-4c8d21037538/231d0c6c-3825-46f4-8afc-fb38d66452d1.png?fm=png&crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.5000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=92&mark-y=405&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTMlMkNGRjc0NDImdz01MjkmaD0zMzImZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Right click on User data - " />
</div>

<div><h3>13. You will get a successfully message</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/9ae5d86a-e555-4af3-abdf-736b0477eac8/bc6c605a-d050-4bef-937a-83792e9072b0.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.5000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=273&mark-y=108&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTMlMkNGRjc0NDImdz0xMTMmaD0xOSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="You will get a successfully message" />
</div>

<div><h3>14. Verify the user data has been loaded by going into the EC2 </h3>
<p>Click on View details</p>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/7760e3ae-0c99-4a3d-b33e-237181a0d82a/4c0748ad-5203-47c9-99b0-2e88dba67873.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.5000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Verify the user data has been loaded by going into the EC2 " />
</div>

<div><h3>15. Copy URL or click on it</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/f42754d8-a58e-409c-8dc1-d67b13821668/d432fc4c-4365-48ec-802c-fbac623a6c4d.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.5000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=845&mark-y=185&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTMlMkNGRjc0NDImdz0zMTImaD0zNSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Copy URL or click on it" />
</div>

<div><h2><a href="https://labs.skillbuilder.aws/sa/lab/arn%3Aaws%3Alearningcontent%3Aus-east-1%3A470679935125%3Ablueprintversion%2FSPL-BE-200-CPBDEC-1%3A1.0.5-d7f74c93/en-US/ae717f00-ab64-4993-bde1-3d3c2cf24255::vM1FiRnnU4DQ6NQQ82o4ga"># Launching Amazon EC2 Instances | Self-Paced Labs</a></h2></div>

<div><h3>16. Verify the user data has been loaded by going into the EC2 </h3>
<p>You should see a message showing the expected output</p>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/d1f4e9a1-832b-4e03-a9e3-24c0198babf2/6418b2be-cd74-45da-9cab-f62147a6a8c1.png?fm=png&crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.5000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=95&mark-y=216&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz04NDAmaD0xNzImZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Verify the user data has been loaded by going into the EC2 " />
</div>

<br/>
<hr/>
<div>

</div>
