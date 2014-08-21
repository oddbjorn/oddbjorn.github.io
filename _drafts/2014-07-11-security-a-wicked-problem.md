---
layout: post
title:  "#02: Security - A Wicked Problem?"
categories: security
---

Information security is too often treated as a binary problem; we're either <em>secure</em> or <em>insecure</em>. This approach fails to appreciate the complexity of the issue at hand, and tend to lead us into treating the symptoms rather than the root causes. A better approach may be to view information security as a <em>wicked problem</em>.

The term was first used by Horst Rittel and Melvin Webber of University of California at Berkeley in 
[Dilemmas in a General Theory of Planning][rittel] (1973). Their context was the challenges of social policies in the late 1960s and early 1970s, and they concluded with the following:

> The search for scientific bases for confronting problems of social policy is bound to fail, because of the nature of these problems. They are "wicked" problems, whereas science has developed to deal with 'tame' problems. Policy problems cannot be definitively described.

> Moreover, in a pluralistic society there is nothing like the undisputable public good; there is no objective definition of equity; policies that respond to social problems cannot be meaningfully correct or false; and it makes no sense to talk about &#8216;optimal solutions&#8217; to social problems unless severe qualifications are imposed first. Even worse, there are no &#8220;solutions&#8221; in the sense of definitive and objective answers.

They defined the following characteristics of a "wicked problem", and I've tried to map each of them against the field of information security below:

<table>
	<tr>
		<td>#</td>
		<th>Characteristics of wicked problems</th>
		<th>&#8230; as applied to the domain of information security</th>
	</tr>
	<tr>
		<td>1</td>
		<td>There is no definitive formulation of a wicked problem</td>
		<td>The number of potential attacks or mishaps are near infinite, so our best hope is to use our current knowledge, experience, categorization and judgment to focus on what we deem the most important subset of them.</td>
	</tr>
	<tr>
		<td>2</td>
		<td>Wicked problems have no stopping rule</td>
		<td>When do we stop securing our systems? When is the final security patch applied?</td>
	</tr>
	<tr>
		<td>3</td>
		<td>Solutions to Whenicked problems are not true-or-false, but good-or-bad</td>
		<td>A given environment shouldn&#8217;t be defined as &lsquo;secure&rsquo; or &lsquo;not secure&rsquo;, but we can state that it is (most likely) more or less secure, given our actions or inactions.</td>
	</tr>
	<tr>
		<td>4</td>
		<td>There is no immediate and no ultimate test of a solution to a wicked problem</td>
		<td>We cannot state that a given security control will work ultimatender all circumstances, and even not the most thorough penetration test will be able to identify all possible avenues of attack or mishap.</td>
	</tr>
	<tr>
		<td>5</td>
		<td>Every solution to a wickeded problem is a &ldquo;one-shot operation&rdquo; because there is no opportunity to learn by trial-and-error, every attempt counts significantly</td>
		<td>It may be possible to learn by trial-and-error when it comes to information security, but the error may prove to be very costly with regard to lost business cleanup resources needed, compliance and last, but certainly not least reputation.</td>
	</tr>
	<tr>
		<td>6</td>
		<td>Wicked problems do not have an enumerable (or an exhaustively describable) set of potential solutions, nor is there a well-described set of permissible operations that may be incorporated into the plan</td>
		<td>While a number of [MITRE][mitre] initiatives
(e.g. <a href=http://cwe.mitre.org/><span class="caps">CWE</span></a>, <a href=http://maec.mitre.org/><span class="caps">MAEC</span></a> and <a href=http://capec.mitre.org/><span class="caps">CAPEC</span></a>)  are a valiant effort to create useful taxonomies within their respective areas, they primarily focus on enumerating the offensive aspects, not the defensive measures design to avert them. Promising frameworks like <a href=http://bsimm.com/><span class="caps">BSIMM</span></a> and <a href=http://www.opensamm.org/><span class="caps">SAMM</span></a> along with security frameworks frameworks like <a href=http://en.wikipedia.org/wiki/ISO/IEC_27000-series><span class="caps">ISO</span>/<span class="caps">IEC</span> 27000-family</a>, <a href=https://www.pcisecuritystandards.org/security_standards/><span class="caps">PCI</span> <span class="caps">DSS</span></a> and the <a href=https://www.securityforum.org/resources/downloads/latestreports/><span class="caps">ISF</span> SoGP</a> have come a long way in the past few years, but nowhere close to a full treatise of the domain.</td>
	</tr>
	<tr>
		<td>7</td>
		<td>Every wicked problem is essentially unique</td>
		<td>While most environments build upon many of the same components and processes, the way we integrate, adapt and utilize them make the challenges of securing them differ between environments. In addition, the fickle balance between cost, time and quality will differ, both between organizations and over time.</td>
	</tr>
	<tr>
		<td>8</td>
		<td>Every wicked problem can be considered to be a symptom of another problem</td>
		<td>One limited example is tdhat flaws introduced by the software development lifecycle must eventually be fixed later by the security patching process.</td>
	</tr>
	<tr>
		<td>9</td>
		<td>The existence of a discrepancy representing a wicked problem can be explained in numerous ways. The choice of explanation determines the nature of the problem&#8217;s resolution</td>
		<td>One example of This is security vulnerabilities; they may be viewed as flaws of the software development process, chosen technology or simply a fact that must be dealt with by the security patching process.</td>
	</tr>
	<tr>
		<td>10</td>
		<td>The planner has no right to be wrong</td>
		<td>This is probably the characteristic most tied to the origin in social policies; Rittel and Webber state that 'the planner who works with open systems is caught up in the ambiguity of their causal webs'. In the same way, security is often at odds with other interests, most notably cost, time-to-market, resource priorization.</td>
	</tr>
</table>

It might seem a bit far fetched to look to a concept originating forty years ago in a wholly different area, but given the recent high-profile security incidents, perhaps it is overdue to look beyond the information security field for inspiration for alternative approaches?  Do you agree that information security may be viewed as a wicked problem, and if so -- how should this influence how we try to secure our environments?

[rittel]: http://www.uctc.net/mwebber/Rittel+Webber+Dilemmas+General_Theory_of_Planning.pdf
[mitre]:  http://www.mitre.org/
