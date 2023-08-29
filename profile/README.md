This is the GitHub organization containing all repositories of the Eclipse Keypop project (Web site https://keypop.org/ & Eclipse Project Management Infrastructure https://projects.eclipse.org/projects/iot.keypop).

 - Keypop offers Java and C++ transcriptions of the APIs for ticketing terminals defined by the Calypso Networks Association (https://calypsonet.org/).
 - The Eclipse Keyple project (https://keyple.org/) provides Java and C++ libraries implementing the Keypop APIs.

# Keypop component repositories for Java and C++ implementations

<table>
	<tbody>
		<tr>
			<th scope="col" rowspan="2">Ticketing terminal layer</th>
			<th scope="col" colspan="3">Keypop project</th>
			<th scope="col" rowspan="2">external interface definition by the Calypso Networks Association</th>
		</tr>
		<tr>
			<th scope="col">Component name</th>
			<th scope="col">Java implementation repository</th>
			<th scope="col">C++ implementation repository</th>
		</tr>
		<tr>
			<td rowspan="2">Reader Layer</td>
			<td>Reader API</td>
			<td><a href="https://github.com/eclipse-keypop/keypop-reader-java-api">keypop-reader-java-api</a></td>
			<td><a href="https://github.com/eclipse-keypop/keypop-reader-cpp-api">keypop-reader-cpp-api</a></td>
			<td><a href="https://calypsonet.github.io/calypsonet-terminal-reader-uml-api/">calypsonet-terminal-reader-uml-api</a></td>
		</tr>
		<tr>
			<td>Card API</td>
			<td><a href="https://github.com/eclipse-keypop/keypop-card-java-api">keypop-card-java-api</a></td>
			<td><a href="https://github.com/eclipse-keypop/keypop-card-cpp-api">keypop-card-cpp-api</a></td>
			<td><a href="https://calypsonet.github.io/calypsonet-terminal-card-uml-api/">calypsonet-terminal-card-uml-api</a></td>
		</tr>
		<tr>
			<td rowspan="4">Calypso Layer</td>
			<td>Calypso Card API</td>
			<td><a href="https://github.com/eclipse-keypop/keypop-calypso-card-java-api">keypop-calypso-card-java-api</a></td>
			<td><a href="https://github.com/eclipse-keypop/keypop-calypso-card-cpp-api">keypop-calypso-card-cpp-api</a></td>
			<td><a href="https://calypsonet.github.io/calypsonet-terminal-calypso-uml-api/">calypsonet-terminal-calypso-card-uml-api</a></td>
		</tr>
		<tr>
			<td>Calypso Symmetric Crypto API</td>
			<td><a href="https://github.com/eclipse-keypop/keypop-calypso-crypto-symmetric-java-api">keypop-calypso-crypto-symmetric-java-api</a></td>
			<td><a href="https://github.com/eclipse-keypop/keypop-calypso-crypto-symmetric-cpp-api">keypop-calypso-crypto-symmetric-cpp-api</a></td>
			<td><a href="https://github.com/calypsonet/calypsonet-terminal-calypso-crypto-symmetric-uml-api">calypsonet-terminal-calypso-crypto-symmetric-uml-api</a></td>
		</tr>
		<tr>
			<td>Calypso Legacy SAM Crypto API</td>
			<td><a href="https://github.com/eclipse-keypop/keypop-calypso-crypto-legacysam-java-api">keypop-calypso-crypto-legacysam-java-api</a></td>
			<td><a href="https://github.com/eclipse-keypop/keypop-calypso-crypto-legacysam-cpp-api">keypop-calypso-crypto-legacysam-cpp-api</a></td>
			<td><a href="https://calypsonet.github.io/calypsonet-terminal-calypso-crypto-legacysam-uml-api/">calypsonet-terminal-calypso-crypto-legacysam-uml-api</a></td>
		</tr>
		<tr>
			<td>Calypso Asymmetric Crypto API</td>
			<td><a href="https://github.com/eclipse-keypop/keypop-calypso-crypto-asymmetric-java-api">keypop-calypso-crypto-asymmetric-java-api</a></td>
			<td><a href="https://github.com/eclipse-keypop/keypop-calypso-crypto-asymmetric-cpp-api">keypop-calypso-crypto-asymmetric-cpp-api</a></td>
			<td><a href="https://github.com/calypsonet/calypsonet-terminal-calypso-crypto-asymmetric-uml-api">calypsonet-terminal-calypso-crypto-asymmetric-uml-api</a></td>
		</tr>
	</tbody>
</table>

# Keypop project support repositories

<table>
	<tbody>
		<tr>
			<th scope="col" colspan="2">Support type</th>
			<th scope="col">Repository</th>
		</tr>
		<tr>
			<td colspan="2">Keypop website https://keypop.org/</td>
			<td><a href="https://github.com/eclipse-keypop/keypop-website">keypop-website</a></td>
		</tr>
		<tr>
			<td colspan="2">Keypop Continuous Integration settings</td>
			<td><a href="https://github.com/eclipse-keypop/keypop-ops">keypop-ops</a></td>
		</tr>
		<tr>
			<td rowspan="2">Repository configuration</td>
			<td>Eclipse-specific</td>
			<td><a href="https://github.com/eclipse-keypop/.eclipsefdn">.eclipsefdn</a></td>
		</tr>
		<tr>
			<td>GitHub-specific</td>
			<td><a href="https://github.com/eclipse-keypop/.github">.github</a></td>
		</tr>
	</tbody>
</table>
