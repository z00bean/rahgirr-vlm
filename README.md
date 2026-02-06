<h1>RAHGIR</h1>

<p><strong>Road-scene Analysis for Hazards with Grounded Interactive Risk Reasoning</strong></p>

<p>
RAHGIR is a policy-conditioned, domain-specialized vision–language reasoning system
designed to analyze forward-facing ego-vehicle road scenes and produce structured,
probabilistic assessments of traffic risk under partial observability.
</p>

<h2>What RAHGIR Does</h2>
<ul>
  <li>Converts a single road image into explicit risk assessments</li>
  <li>Reasons from the ego-vehicle perspective using traffic-domain constraints</li>
  <li>Produces calibrated Low / Medium / High risk estimates with justifications</li>
</ul>

<h2>Key Capabilities</h2>
<ul>
  <li>Policy-conditioned hazard reasoning grounded in visual evidence</li>
  <li>Explicit modeling of interaction risk between traffic agents</li>
  <li>Occlusion-aware risk inference under incomplete observability</li>
  <li>Structured, evaluation-friendly outputs (not free-form captions)</li>
</ul>

<h2>Reasoning Modes</h2>
<ul>
  <li><strong>Observed-agent risk</strong>: Risk estimation conditioned on visible road users</li>
  <li><strong>Hypothetical-agent risk</strong>: Risk estimation under potential agent emergence from occluded regions</li>
</ul>

<p>
RAHGIR is implemented on AWS with explicit reasoning policies,
guardrails, calibration layers, and an evaluation harness.
  <!-- that mirrors a fine-tuned vision-language model pipeline—without model retraining. -->
</p>
