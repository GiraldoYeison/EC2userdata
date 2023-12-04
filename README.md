# EC2userdata
Creating an AWS EC2 instance with user data

# EC2userdata
Launching EC2 Instances and test user data

<h1>Launching EC2 Instances and test user data</h1>

<div><b>Creation Date:</b> October 18, 2023</div>
<div><b>Created By:</b> Yeison Giraldo</div>


<div style="height: 24px">&#8203;</div>
<hr />
<div style="height: 24px">&#8203;</div>


<div><h3>1. Click on Launch instances</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/09e91603-9054-4011-befe-8bc337ca2118/00b13ba0-e1ee-4372-82e5-4c10fac93ef0.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.9237&fp-y=0.0719&fp-z=2.9427&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=765&mark-y=101&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0zMzImaD03OCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Launch instances" />
</div>

<div><h3>2. Type "myWebServer"</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/fb2a8902-0841-4f08-bfa9-8d62531b70ce/b104ed9c-8bca-4477-b80d-88f05ff2c967.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2280&fp-y=0.3761&fp-z=1.5654&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=110&mark-y=308&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02MzYmaD00NiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Type &quot;myWebServer&quot;" />
</div>

<div><h3>3. Click on Add additional tags</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/eb530b11-5b1d-418a-b206-c928b075b88c/973ccebc-e76a-4131-a5d9-f1b7a53892f7.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.4451&fp-y=0.3739&fp-z=2.6275&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=473&mark-y=302&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0yNTQmaD01OCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Add additional tags" />
</div>

<div><h3>4. Click on Select resource types</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/bf341cff-3f0a-465b-be4c-2acb04f81dee/090e8781-0845-44f3-8471-5811e3c04e5f.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.3434&fp-y=0.3960&fp-z=2.4506&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=441&mark-y=295&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0zMTgmaD03MiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Select resource types" />
</div>

<div><h3>5. Click on Network interfaces…</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/75f3fc3a-b270-45ec-a8a7-de04ddeadeb4/72d689f5-8909-43d5-ad6d-b9d154507433.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.3477&fp-y=0.5697&fp-z=2.4004&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=432&mark-y=294&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0zMzYmaD03NCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Network interfaces…" />
</div>

<div><h3>6. Click on Quick Start</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/355411df-a6ab-48e9-806c-5a75e97e2a40/6da1f385-5697-4daf-b154-f2a45903be32.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2860&fp-y=0.5299&fp-z=1.3248&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=93&mark-y=126&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz03MjMmaD00MTAmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Quick Start" />
</div>

<div><h3>7. Click on Amazon Linux</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/143cbece-1cdb-4a5a-9479-d1db90b4899b/b2e09892-44f5-4510-970e-2c573aae44bb.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.0922&fp-y=0.3883&fp-z=2.2310&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=165&mark-y=222&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0xNjMmaD0yMTkmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Amazon Linux" />
</div>

<div><h3>8. Click on t2.micro…</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/db051b26-2073-41b9-8ff4-f99919ec0619/f439f34f-4c81-49ae-bcf4-f91534400c8b.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2253&fp-y=0.6715&fp-z=1.5789&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=111&mark-y=262&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02MzImaD0xMzkmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on t2.micro…" />
</div>

<div><h3>9. Click on t3.micro…</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/d2829d54-9f4b-4303-b308-bc52daf6d682/1381e124-25d0-49c9-adf2-09643a6c9746.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2201&fp-y=0.3816&fp-z=1.6053&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=113&mark-y=261&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02MjImaD0xNDEmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on t3.micro…" />
</div>

<div><h3>10. Click on Select</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/24e4f84d-f3a6-4bd0-8167-3f089a8ff531/b2323703-bc21-4af9-b5e7-9fa89cfabef6.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2253&fp-y=0.5708&fp-z=1.5789&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=111&mark-y=308&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02MzImaD00NiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Select" />
</div>

<div><h3>11. Click on AWSLabsKeyPair-nLUQRGfr26AkvGhSYuojFN…</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/ef24fe48-85ba-48bf-bcaa-5705e7a01d58/2ac99089-655b-4b36-b8e9-8c36d18a1446.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2253&fp-y=0.6858&fp-z=1.5789&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=111&mark-y=300&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02MzImaD02NyZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on AWSLabsKeyPair-nLUQRGfr26AkvGhSYuojFN…" />
</div>

<div><h3>12. Click on Network settings Info…</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/2c6af974-ef57-45bc-bf11-4bd3b2d41f5d/354561ad-17b2-481c-a365-5496a324809b.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2860&fp-y=0.4845&fp-z=1.1974&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=84&mark-y=78&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02NTMmaD01MDcmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Network settings Info…" />
</div>

<div><h3>13. Click on Edit</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/416e6527-147b-4ec1-a271-f63141ca480f/585fb4da-74ff-4248-9269-a430ee81962c.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.4899&fp-y=0.1150&fp-z=2.8818&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=519&mark-y=177&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0xNjMmaD04NCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Edit" />
</div>

<div><h3>14. Click on vpc-02fadc7b31a4c12cf…</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/31fe273b-7c4f-438c-90a5-9e29b6b6dee8/85b7eaff-5c10-485f-8771-030096957620.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2253&fp-y=0.2135&fp-z=1.5789&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=111&mark-y=191&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02MzImaD02NSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on vpc-02fadc7b31a4c12cf…" />
</div>

<div><h3>15. Click on vpc-024127ae0021afb79 (EC2-Lab-VPC)…</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/821a7dd6-70b8-40fb-ba8f-990ec5b9db67/4dc8256d-973e-434a-a2b0-c8ace731a131.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2253&fp-y=0.3551&fp-z=1.5789&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=111&mark-y=298&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02MzImaD02NyZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on vpc-024127ae0021afb79 (EC2-Lab-VPC)…" />
</div>

<div><h3>16. Click on subnet-04ad97a796d6ed1c1…</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/038d86ef-d8c2-4a1d-bacd-93969ae0a72f/e7539a93-ac7c-47c7-a6d6-68120b21a646.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2253&fp-y=0.3131&fp-z=1.5789&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=111&mark-y=286&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02MzImaD04MyZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on subnet-04ad97a796d6ed1c1…" />
</div>

<div><h3>17. Click on subnet-0e79acb287e2fa793…</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/80385399-b70a-4e87-9c9f-3c1d9ade916a/e265d4cb-2687-4302-aca7-dd5c90df83b3.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2253&fp-y=0.4889&fp-z=1.5789&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=111&mark-y=289&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02MzImaD04MyZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on subnet-0e79acb287e2fa793…" />
</div>

<div><h3>18. Click on Firewall (security groups)  Info</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/2f8ae19d-68d0-46e4-aa4c-731fcac43e8d/0e246590-1f96-4721-aabd-7b1df06ac0b4.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2280&fp-y=0.5277&fp-z=1.5654&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=110&mark-y=292&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02MzYmaD03OCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Firewall (security groups)  Info" />
</div>

<div><h3>19. Click on Select security groups</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/2bc32551-6aa8-4077-9a1a-d1aa15c82dae/7e7cc0f6-9ac1-48ae-9023-1eba3ddbea3e.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2253&fp-y=0.6184&fp-z=1.5789&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=111&mark-y=308&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02MzImaD00NiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Select security groups" />
</div>

<div><h3>20. Click on LabSG…</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/0791675c-1840-4a77-8c59-018b331fdb58/197d6bbc-040e-4c34-b0ed-32bc0c7805db.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2253&fp-y=0.7511&fp-z=1.5789&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=111&mark-y=368&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02MzImaD02NyZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on LabSG…" />
</div>

<div><h3>21. Select Storage size</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/3cf32e6a-6420-4753-9123-32c985ccfc93/596bb962-7edb-481e-9b05-0bfcb3ee06eb.jpg?fm=png&q=100&crop=focalpoint&fit=crop&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Select Storage size" />
</div>

<div><h3>22. Type "30"</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/85a90383-12dd-4614-9f37-55407a6ce9e7/4dddbc7c-bee3-4eea-939c-6757abfb9fde.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.1319&fp-y=0.8319&fp-z=2.2395&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=158&mark-y=380&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0zOTQmaD02NiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Type &quot;30&quot;" />
</div>

<div><h3>23. Click on Advanced details Info</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/26f0f648-cefa-41c5-a2cc-78f1ae1e0154/82365e14-50fd-4727-8cdc-770fa77d867b.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2860&fp-y=0.9071&fp-z=1.2833&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=71&mark-y=549&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz03MzgmaD02OCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Advanced details Info" />
</div>

<div><h3>24. Click on Select</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/ce1ea2de-e427-487f-bc50-a00a2aeedee4/db016015-5265-43c7-bd3b-bebf33de0e8a.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2253&fp-y=0.8595&fp-z=1.5789&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=111&mark-y=492&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02MzImaD00NiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Select" />
</div>

<div><h3>25. Click on SSMInstanceProfile…</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/3d3794fb-0495-412b-8ee8-75b9c1f28c6b/62c67979-3d0b-4afe-99fd-de1b15714afa.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2253&fp-y=0.8142&fp-z=1.5789&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=111&mark-y=434&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02MzImaD02NyZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on SSMInstanceProfile…" />
</div>

<div><h3>26. Right click on User data - optional  Info</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/b3853f95-295a-47cc-b048-5688beb9480f/590c1680-602c-4f5c-96fe-5aae474b0f67.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2280&fp-y=0.7135&fp-z=1.5654&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=110&mark-y=166&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02MzYmaD0zOTkmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Right click on User data - optional  Info" />
</div>

<div><h3>27. Paste text area</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/c267c2bb-6e1a-4946-9e27-4c8d21037538/1e47b0d4-7007-4e5d-8f90-5f4e07ba7a48.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2280&fp-y=0.7135&fp-z=1.5654&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=110&mark-y=166&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02MzYmaD0zOTkmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Paste text area" />
</div>

<div><h3>28. Click on Launch instance</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/4a8a7760-2deb-4ce7-9771-68eb4ee2a7bb/ff7c7804-57d9-45cb-992d-4a9a1137d4c9.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.7076&fp-y=0.8584&fp-z=2.9302&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=428&mark-y=345&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0zNDMmaD04NiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Launch instance" />
</div>

<div><h3>29. Click on i-0920561bb34c2d65e</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/9ae5d86a-e555-4af3-abdf-736b0477eac8/bc6c605a-d050-4bef-937a-83792e9072b0.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2741&fp-y=0.1781&fp-z=2.5380&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=457&mark-y=275&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0yODYmaD00OCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on i-0920561bb34c2d65e" />
</div>

<div><h3>30. Click on Actions</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/2767a61a-b6bb-46e0-b664-82bf96d49379/2a2d98a8-fc47-4a7d-8b55-c39f75004e06.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.8397&fp-y=0.0719&fp-z=2.9427&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=504&mark-y=101&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0yNjEmaD03OCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Actions" />
</div>

<div><h3>31. Click on View details</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/3db2739c-a477-4cab-b98b-aebe53c74cae/3bd0cc6e-15b4-4ca5-8fdb-f1310d6d95ce.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.8800&fp-y=0.1394&fp-z=2.9237&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=510&mark-y=229&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz01MzgmaD04MSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on View details" />
</div>

<div><h3>32. Check on</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/5d7b9208-212e-4c68-af56-891bddc22f58/73869553-897c-4efb-9770-cb4f16a06611.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.1630&fp-y=0.2389&fp-z=3.0832&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=575&mark-y=306&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz01MCZoPTUwJmZpdD1jcm9wJmNvcm5lci1yYWRpdXM9MTA%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Check on" />
</div>

<div><h3>33. Click on Actions</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/22ba1bf6-38b1-43da-bbdc-5d50f956ea29/e55241bc-e9a9-450a-9f82-862f941e72c8.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.8397&fp-y=0.0719&fp-z=2.9427&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=504&mark-y=101&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0yNjEmaD03OCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Actions" />
</div>

<div><h3>34. Click on View details</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/7760e3ae-0c99-4a3d-b33e-237181a0d82a/4c0748ad-5203-47c9-99b0-2e88dba67873.jpg?fm=png&q=100&crop=focalpoint&fit=crop&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on View details" />
</div>

<div><h3>35. Click on open address </h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/f42754d8-a58e-409c-8dc1-d67b13821668/d432fc4c-4365-48ec-802c-fbac623a6c4d.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.8339&fp-y=0.3053&fp-z=2.8321&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=194&mark-y=281&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz04ODQmaD0xMDAmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on open address " />
</div>

<div><h2><a href="https://labs.skillbuilder.aws/sa/lab/arn%3Aaws%3Alearningcontent%3Aus-east-1%3A470679935125%3Ablueprintversion%2FSPL-BE-200-CPBDEC-1%3A1.0.5-d7f74c93/en-US/ae717f00-ab64-4993-bde1-3d3c2cf24255::vM1FiRnnU4DQ6NQQ82o4ga"># Launching Amazon EC2 Instances | Self-Paced Labs</a></h2></div>

<div><h3>36. Click on PHP Application Page</h3>
<img src="https://images.tango.us/workflows/5b91bc2d-e2c4-4b01-ab39-e1a2fa432e42/steps/d1f4e9a1-832b-4e03-a9e3-24c0198babf2/ec741776-8e64-4a29-bc74-0c13358232d9.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.5767&fp-y=0.5414&fp-z=1.5101&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=167&mark-y=295&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz04NjYmaD0xNzcmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on PHP Application Page" />
</div>

<div><h2><a href="https://us-west-2.console.aws.amazon.com/ec2/home?region=us-west-2#LaunchInstances:"># Launch an instance | EC2 | us-west-2</a></h2></div>

<div><h2><a href="https://us-west-2.console.aws.amazon.com/ec2/home?region=us-west-2#LaunchInstances:"># Launch an instance | EC2 | us-west-2</a></h2></div>

<br/>
<hr/>
<div>

</div>
