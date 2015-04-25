# markdown-test
playground for testing github markdown

Unfortunately [GFM](https://help.github.com/articles/github-flavored-markdown/) does not support table colspans, what makes it usage a little bit probelmatic. It is , however, possible to use HTML tables - yes, of course, we never wanted to type tables again and so we invented a cool markdown alternative, but, hey, why not implement just a subset? At least there still needs to be something left to annoy people!

A big HTML table might look like this: 
view-source: https://www.process-one.net/en/ejabberd/protocols/


<table class="table table-striped table-bordered">
	<tbody>
		<thead>

			<th width="10%">Reference</th>
			<th width="25%">Title</th>
			<th width="25%">Description</th>
			<th width="15%">Community Server (eCS)</th>
			<th width="15%">Business Edition (eBE)</th>
		</thead>
		<tr>

			<th align="left" colspan="5">Core XMPP specifications</th>
		</tr>
		<tr>

			<td>RFC-3920</td>
			<td>XMPP: Core</td>
			<td>XMPP Core mechanisms and routing</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>RFC-3921</td>
			<td>XMPP: Instant Messaging and Presence</td>
			<td>XMPP IM and presence</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>RFC-6120</td>
			<td>XMPP: Core</td>
			<td>XMPP Core mechanisms and routing (update)</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>RFC-6121</td>
			<td>XMPP: Instant Messaging and Presence</td>
			<td>XMPP IM and presence (update)</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>RFC-6122</td>
			<td>XMPP: Address Format</td>
			<td>Format for user and services addresses</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<th align="left" colspan="5">Server compliance</th>
		</tr>
		<tr>

			<td>XEP-0212</td>
			<td>XMPP Basic Server 2008</td>
			<td></td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0216</td>
			<td>XMPP Intermediate Server 2008</td>
			<td></td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0243</td>
			<td>XMPP Server Compliance 2009</td>
			<td></td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0270</td>
			<td>XMPP Compliance Suites 2010</td>
			<td></td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0302</td>
			<td>XMPP Compliance Suites 2012</td>
			<td></td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<th align="left" colspan="5">External IETF specifications (non-XMPP)</th>
		</tr>
		<tr>

			<td>RFC-5802</td>
			<td>Salted Challenge Response (SCRAM) SASL and GSS-API Mechanism</td>
			<td>Secure authentication methods</td>
			<td class="tick">SCRAM only</td>
			<td class="tick">SCRAM only</td>
		</tr>
		<tr>

			<td>RFC-5766</td>
			<td>Session Traversal Utilities for NAT (STUN)</td>
			<td>Technique for easier binary session parameters negociation</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>RFC-5766</td>
			<td>Traversal Using Relays around NAT (TURN)</td>
			<td>Technique for binary data relay</td>
			<td></td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>RFC-5245</td>
			<td>Interactive Connectivity Establishment (ICE)</td>
			<td>Technique mixing STUN and TURN</td>
			<td></td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>RFC-6455</td>
			<td>The WebSocket protocol</td>
			<td>For web-based clients, real time bidirectional in-browser protocol</td>
			<td class="tick">&#10004;</td>
				<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<th align="left" colspan="5">Privacy</th>
		</tr>
		<tr>

			<td>XEP-0016</td>
			<td>Privacy Lists</td>
			<td>Personal rules to prevent spam and abuse, and protect privacy (for example
				invisibility)</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0018</td>
			<td>Invisible Presence (rejected)</td>
			<td>Removed in next version 3.0, use of privacy lists encouraged</td>
			<td class="tick">&#10004;</td>
			<td></td>
		</tr>
		<tr>

			<td>XEP-0191</td>
			<td>Simple Communication Blocking</td>
			<td>Simple messages blocker</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<th align="left" colspan="5">Multi-User Chat</th>
		</tr>
		<tr>

			<td>XEP-0045</td>
			<td>Multi-User Chat</td>
			<td>For conferences with multiple users, with a large number of features (privacy,
				security, invitations, etc.)</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0045</td>
			<td>Multi-User Chat Perfomance</td>
			<td>Performance and true clustering</td>
			<td></td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<th align="left" colspan="5">Web</th>
		</tr>
		<tr>

			<td>XEP-0124</td>
			<td>Bidirectional-streams Over Synchronous HTTP (BOSH) - HTTP Binding</td>
			<td>Long polling technique for web clients</td>
				<td class="tick">&#10004;</td>
				<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0206</td>
			<td>XMPP Over BOSH</td>
			<td>For web-based client, long-polling technique</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0206</td>
			<td>XMPP Over BOSH Performance</td>
			<td>Performance</td>
			<td></td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0025</td>
			<td>Jabber HTTP Polling (obsolete -&gt; XEP-0124)</td>
			<td>Old technique for web-based clients</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<th align="left" colspan="5">VoIP</th>
		</tr>
		<tr>

			<td>XEP-0278</td>
			<td>Jingle Relay Nodes (experimental)</td>
			<td>A powerful Skype-like P2P technique for VoIP</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0176</td>
			<td>Jingle ICE-UDP Transport Method</td>
			<td>Technique for NAT traversal, see STUN and TURN(VoIP and binary exchanges)</td>
			<td class="tick">&#10004;</td>
				<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<th align="left" colspan="5">Publish-Subscribe</th>
		</tr>
		<tr>

			<td>XEP-0060</td>
			<td>Publish-Subscribe</td>
			<td>Publish and subscribe pattern applied to XMPP</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0060</td>
			<td>Publish-Subscribe Performance</td>
			<td>Flexible and highly scalable</td>
			<td></td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0222</td>
			<td>Persistent Storage of Public Data via PubSub</td>
			<td>Best practices to persistently store semi-public data objects such as
				public keys and personal profiles</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0223</td>
			<td>Persistent Storage of Private Data via PubSub</td>
			<td>Best practices to persistently store private information such as bookmarks
				and client configuration options</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0248</td>
			<td>PubSub Collection Nodes</td>
			<td>Broadcast of pubsub event in a network of pubsub interdependent nodes</td>
			<td></td>
				<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0163</td>
			<td>Personal Eventing Protocol</td>
			<td>Personal events like location, modd, activity, etc.</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<th align="left" colspan="5">Security</th>
		</tr>
		<tr>

			<td>XEP-0077</td>
			<td>In-band Registration</td>
			<td>For account creations, from the XMPP client</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0158</td>
			<td>CAPTCHA Forms</td>
			<td>Additional security to prevent bot massive operations</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0027</td>
			<td>Current Jabber OpenPGP Usage</td>
			<td>Client-side end-to-end encryption</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>P1-Spec</td>
			<td>Traffic shapers</td>
			<td>Bandwidth restriction policy for server's incoming traffic</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<th align="left" colspan="5">Administration</th>
		</tr>
		<tr>

			<td>XEP-0004</td>
			<td>Data Forms</td>
			<td>Queries and responses between entities, with forms</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0050</td>
			<td>Ad-Hoc Commands</td>
			<td>Sequences of forms (like wizards) for automated data exchange (human to
				machine, machine to machine)</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0114</td>
			<td>Jabber Component Protocol</td>
			<td>Plugin-like interface for server-side software components</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0133</td>
			<td>Service Administration</td>
			<td>Server message broadcast and client-side server configuration</td>
			<td class="tick">&#10004;</td>
				<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<th align="left" colspan="5">Mobile</th>
		</tr>
		<tr>

			<td>P1-Spec</td>
			<td>Out-of-reception state</td>
			<td>Mechanism to keep connection state on the server side, independently of
				the current network state</td>
			<td></td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>P1-Spec</td>
			<td>Fast reconnect ("rebind")</td>
			<td>Mechanism to reattach to an existing session when mobile is getting reconnected
				on the network</td>
			<td></td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>P1-Spec</td>
			<td>Apple push</td>
			<td>Message notification for iOS devices (iPhone, iPad, iPod Touch)</td>
			<td></td>
				<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>P1-Spec</td>
			<td>Acknowledgements and replay</td>
			<td>Message reliability: no message can be lost even under network inconsistencies</td>
			<td></td>
				<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>P1-Spec</td>
			<td>End-to-end traceability</td>
			<td>Message indicator (status: sent, delivered, offline, which server has
				been reached...)</td>
			<td></td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>P1-Spec</td>
			<td>Multidevice and archiving</td>
			<td>Message replication and synchronization across devices</td>
			<td></td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0237</td>
			<td>Roster Versioning</td>
			<td>Reduce bandwith consumption by limiting contact details download</td>
			<td></td>
				<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0280</td>
			<td>Message Carbons</td>
			<td>Send copy of your own messages to other connected resources</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<th align="left" colspan="5">Performance and scalability</th>
		</tr>
		<tr>

			<td>P1-Spec</td>
			<td>Clustering</td>
			<td>Unique clustering mode with no single point of failure. This is true active
				- active service for scalability and fault-tolerance</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>P1-Spec</td>
			<td>Consistent hash clustering</td>
			<td>Low latency, higher performance clustering method to build large scale
				platform</td>
			<td></td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<th align="left" colspan="5">Status</th>
		</tr>
		<tr>

			<td>XEP-0012</td>
			<td>Last Activity</td>
			<td>Date of the last activity of an entity before going offline</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0172</td>
			<td>User Nickname</td>
			<td>Nickname metadata</td>
			<td></td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<th align="left" colspan="5">XMPP extensions</th>
		</tr>
		<tr>

			<td>XEP-0004</td>
			<td>Data Forms</td>
			<td>Queries and responses between entities, with forms</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0013</td>
			<td>Flexible Offline Message Retrieval</td>
			<td>Filter offline messages, to prevent storm when reconnecting</td>
			<td></td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0020</td>
			<td>Feature Negotiation</td>
			<td>Discovery of component feature</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0022</td>
			<td>Message Events</td>
			<td>Acknowledgements (feature implemented in mobile specs above)</td>
			<td></td>
			<td></td>
		</tr>
		<tr>

			<td>XEP-0023</td>
			<td>Message Expiration</td>
			<td>Expiry time of offline message</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0030</td>
			<td>Service Discovery</td>
			<td>To query entity's features and capabilities</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0033</td>
			<td>Extended Stanza Addressing</td>
			<td>To send messages to multiple recepients, like email's to:, cc: and bcc:
				lists</td>
			<td></td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0039</td>
			<td>Statistics Gathering</td>
			<td>To query statistics of services</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0049</td>
			<td>Private XML Storage</td>
			<td>For server-side storage of simple XML like config options</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0054</td>
			<td>vcard-temp</td>
			<td>For vCards (business cards) storage and queries</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0055</td>
			<td>Jabber Search</td>
			<td>Forms dedicated to search</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0059</td>
			<td>Result Set Management</td>
			<td>Paging of large results sets</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0065</td>
			<td>SOCKS5 Bytestreams</td>
			<td>Relay for file transfers</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0070</td>
			<td>Verifying HTTP Requests via Jabber</td>
			<td>CAPTCHA-like technique to prevent abuse</td>
			<td></td>
			<td></td>
		</tr>
		<tr>

			<td>XEP-0078</td>
			<td>Non-SASL Authentication</td>
			<td>Authentication method</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0082</td>
			<td>XMPP Date and Time Profiles</td>
			<td>Standard 08601 for dates</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0085</td>
			<td>Chat State Notifications</td>
			<td>Typing indicator</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0086</td>
			<td>Error Condition Mappings</td>
			<td>Error codes definition</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0090</td>
			<td>Legacy Entity Time</td>
			<td>Compliance with previous Jabber protocole</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0091</td>
			<td>Legacy Delayed Delivery</td>
			<td>Compliance with previous Jabber protocole</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0092</td>
			<td>Software Version</td>
			<td>Discovery of software release numbers</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0100</td>
			<td>Gateway Interaction</td>
			<td>Interoperability with private communities : Microsoft MSN/WLM, Yahoo!
				Messenger, ICQ, AOL IM, IRC, Twitter</td>
			<td></td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0106</td>
			<td>JID Escaping</td>
			<td>Ability to use email address as user name</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0115</td>
			<td>Entity Capabilities</td>
			<td>Discovery of client capabilities</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0128</td>
			<td>Service Discovery Extensions</td>
			<td>Extra information and services</td>
			<td></td>
			<td></td>
		</tr>
		<tr>

			<td>XEP-0130</td>
			<td>Waiting Lists</td>
			<td>Discovery of IM contacts by phone numbers, email addresses,...</td>
			<td></td>
				<td></td>
		</tr>
		<tr>

			<td>XEP-0131</td>
			<td>Stanza Headers and Internet Metadata</td>
			<td>Encoding other protocols inside XMPP like SIP, MIME, email,...</td>
			<td></td>
				<td></td>
		</tr>
		<tr>

			<td>XEP-0137</td>
			<td>Publishing SI Requests</td>
			<td>Pull-oriented file transfer</td>
			<td></td>
			<td></td>
		</tr>
		<tr>

			<td>XEP-0138</td>
			<td>Stream Compression</td>
			<td>Limit bandwith consumption used by XMPP protocole</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0157</td>
			<td>Contact Addresses for XMPP Services</td>
			<td>Discover server admin contact detail</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0160</td>
			<td>Best Practices for Handling Offline Messages</td>
			<td>Best Practices for Handling Offline Messages</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0170</td>
			<td>Recommended Order of Stream Feature Negotiation</td>
			<td>Recommended Order of Stream Feature Negotiation</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0175</td>
			<td>Best Practices for Use of SASL ANONYMOUS</td>
			<td>Authentication method for user without account</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0178</td>
			<td>Best Practices for Use of SASL EXTERNAL</td>
			<td>Authentication method</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0185</td>
			<td>Dialback Key Generation and Validation</td>
			<td>Algorithm to use when dialbacking</td>
			<td></td>
			<td></td>
		</tr>
		<tr>

			<td>XEP-0190</td>
			<td>Best Practice for Closing Idle Streams</td>
			<td>Best Practice for Closing Idle Streams</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0198</td>
			<td>Stream Management</td>
			<td>Using ProcessOne custom mobile stacks instead</td>
			<td></td>
			<td></td>
		</tr>
		<tr>

			<td>XEP-0199</td>
			<td>XMPP Ping</td>
			<td>A ping technique specific to XMPP</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0202</td>
			<td>Entity Time</td>
			<td>To query one's entity local time</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0203</td>
			<td>Delayed Delivery</td>
			<td>Offline message timestamp</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0205</td>
			<td>Best Practices to Discourage Denial of Service Attacks</td>
			<td>Best Practices to Discourage Denial of Service Attacks plus other protection
				mechanisms</td>
			<td></td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0215</td>
			<td>External Service Discovery</td>
			<td>Discovery of extra-services addresses (TURN,...)</td>
			<td></td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0220</td>
			<td>Server Dialback</td>
			<td>Workflow to use when dialbacking</td>
			<td></td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0225</td>
			<td>Component Connections</td>
			<td>New protocole to connect components to XMPP servers</td>
			<td></td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0227</td>
			<td>Portable Import/Export Format for XMPP-IM Servers</td>
			<td>Import/Export for server data</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
		<tr>

			<td>XEP-0279</td>
			<td>Server IP Check</td>
			<td>Client can ask server its IP address mostly for VoIP services</td>
			<td class="tick">&#10004;</td>
			<td class="tick">&#10004;</td>
		</tr>
	</tbody>
</table>

