# awesome-windsurf-rule-set

## Combined Windsurf Model Cost Analysis (Sorted by AI Model)

<table>
<thead>
<tr>
<th>Billing Category</th>
<th>Reasoning Type</th>
<th>Vendor</th>
<th>Model Family</th>
<th>Specific Model</th>
<th>Base Cost</th>
<th>Formula</th>
<th>Small Task


<em>(~1 Loop)</em></th>
<th>Medium Task


<em>(~5 Loops)</em></th>
<th>Complex Refactor


<em>(~15 Loops)</em></th>
</tr>
</thead>
<tbody>

<tr>
<td rowspan="4"><strong>BYOK API</strong></td>
<td rowspan="2"><strong>Standard</strong></td>
<td rowspan="2">Anthropic (Claude)</td>
<td> Opus</td>
<td>4</td>
<td>$5 In / $25 Out*</td>
<td>&Sigma; (Tokens &times; Rate) per loop</td>
<td>$0.08</td>
<td>$0.75</td>
<td>$5.00</td>
</tr>
<tr>
<td> Sonnet</td>
<td>4</td>
<td>$3 In / $15 Out*</td>
<td>&Sigma; (Tokens &times; Rate) per loop</td>
<td>$0.05</td>
<td>$0.45</td>
<td>$3.00</td>
</tr>

<tr>
<td rowspan="2"><strong>Think</strong></td>
<td rowspan="2">Anthropic (Claude)</td>
<td> Opus</td>
<td>4</td>
<td>$5 In / $25 Out*</td>
<td>&Sigma; (Tokens &times; Rate) + Think Tokens</td>
<td>$0.15</td>
<td>$1.50</td>
<td>$8.00</td>
</tr>
<tr>
<td> Sonnet</td>
<td>4</td>
<td>$3 In / $15 Out*</td>
<td>&Sigma; (Tokens &times; Rate) + Think Tokens</td>
<td>$0.09</td>
<td>$0.90</td>
<td>$4.80</td>
</tr>

<tr>
<td rowspan="13"><strong>Flat-Rate</strong></td>

<td rowspan="9"><strong>Standard</strong></td>

<td rowspan="4">Anthropic (Claude)</td>
<td rowspan="2"> Opus</td>
<td>4.5</td>
<td>4 credits</td>
<td>Credits &times; $0.04 &times; Loops</td>
<td>$0.16</td>
<td>$0.80</td>
<td>$2.40</td>
</tr>
<tr>
<td>4.6</td>
<td>6 credits</td>
<td>Credits &times; $0.04 &times; Loops</td>
<td>$0.24</td>
<td>$1.20</td>
<td>$3.60</td>
</tr>
<tr>
<td rowspan="2"> Sonnet</td>
<td>4.5</td>
<td>2 credits</td>
<td>Credits &times; $0.04 &times; Loops</td>
<td>$0.08</td>
<td>$0.40</td>
<td>$1.20</td>
</tr>
<tr>
<td>4.6</td>
<td>4 credits</td>
<td>Credits &times; $0.04 &times; Loops</td>
<td>$0.16</td>
<td>$0.80</td>
<td>$2.40</td>
</tr>

<tr>
<td rowspan="2">Windsurf</td>
<td>Cascade</td>
<td>Base</td>
<td>0 credits</td>
<td>Credits &times; $0.04 &times; Loops</td>
<td>$0.00</td>
<td>$0.00</td>
<td>$0.00</td>
</tr>
<tr>
<td>SWE</td>
<td>1 / 1 Lite</td>
<td>0 credits</td>
<td>Credits &times; $0.04 &times; Loops</td>
<td>$0.00</td>
<td>$0.00</td>
<td>$0.00</td>
</tr>

<tr>
<td>Google</td>
<td>Gemini</td>
<td>2.5 Pro</td>
<td>1 credit</td>
<td>Credits &times; $0.04 &times; Loops</td>
<td>$0.04</td>
<td>$0.20</td>
<td>$0.60</td>
</tr>

<tr>
<td rowspan="2">OpenAI</td>
<td rowspan="2">GPT</td>
<td>5.3-Codex</td>
<td>2 credits</td>
<td>Credits &times; $0.04 &times; Loops</td>
<td>$0.08</td>
<td>$0.40</td>
<td>$1.20</td>
</tr>
<tr>
<td>5.4 (Low Reason)</td>
<td>1.5 credits</td>
<td>Credits &times; $0.04 &times; Loops</td>
<td>$0.06</td>
<td>$0.30</td>
<td>$0.90</td>
</tr>

<tr>
<td rowspan="4"><strong>Think</strong></td>
<td rowspan="4">Anthropic (Claude)</td>
<td rowspan="3"> Opus</td>
<td>4.6</td>
<td>8 credits</td>
<td>Credits &times; $0.04 &times; Loops</td>
<td>$0.32</td>
<td>$1.60</td>
<td>$4.80</td>
</tr>
<tr>
<td>4.6 (Fast)</td>
<td>12 credits</td>
<td>Credits &times; $0.04 &times; Loops</td>
<td>$0.48</td>
<td>$2.40</td>
<td>$7.20</td>
</tr>
<tr>
<td>4.6 (1M)</td>
<td>20 credits</td>
<td>Credits &times; $0.04 &times; Loops</td>
<td>$0.80</td>
<td>$4.00</td>
<td>$12.00</td>
</tr>
<tr>
<td> Sonnet</td>
<td>4.6</td>
<td>6 credits</td>
<td>Credits &times; $0.04 &times; Loops</td>
<td>$0.24</td>
<td>$1.20</td>
<td>$3.60</td>
</tr>
</tbody>
</table>