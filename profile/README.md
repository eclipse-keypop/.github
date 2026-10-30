# Eclipse Keypop

This is the GitHub organization containing all repositories of the [Eclipse Keypop project](http://keypop.org/).

 - Keypop offers Java and C++ transcriptions of the '[Ticketing Terminal APIs](https://terminal-api.calypsonet.org/)' defined by the [Calypso Networks Association](https://calypsonet.org/).
 - The [Eclipse Keyple project](https://keyple.org/) provides Java and C++ libraries implementing the Keypop APIs.

## Keypop component repositories for Java and C++ implementations

<table>
	<tbody>
		<tr>
			<th scope="col" rowspan="2">Ticketing terminal layer</th>
			<th scope="col" colspan="4">Keypop project</th>
			<th scope="col" rowspan="2">external CNA definition</th>
		</tr>
		<tr>
			<th scope="col">Component name</th>
			<td></td>
			<th scope="col">Java implementation repository</th>
			<th scope="col">C++ implementation repository</th>
		</tr>
		<tr>
			<td rowspan="4">Reader Layer</td>
			<td rowspan="2">Reader API</td>
			<th scope="row">API Doc</th>
			<td><a href="https://docs.keypop.org/keypop-reader-java-api">Java Doc</a></td>
			<td><a href="https://docs.keypop.org/keypop-reader-cpp-api/">C++ Doc</a></td>
			<td><a href="https://docs.terminal-api.calypsonet.org/reader/">Specification</a></td>
		</tr>
		<tr>
			<th scope="row">Repository</th>
			<td><a href="https://github.com/eclipse-keypop/keypop-reader-java-api">keypop-reader-java-api</a></td>
			<td><a href="https://github.com/eclipse-keypop/keypop-reader-cpp-api">keypop-reader-cpp-api</a></td>
			<td><a href="https://docs.terminal-api.calypsonet.org/reader">calypsonet-terminal-reader-api-spec</a></td>
		</tr>
		<tr>
			<td rowspan="2">Card API</td>
			<th scope="row">API Doc</th>
			<td><a href="https://docs.keypop.org/keypop-card-java-api/">Java Doc</a></td>
			<td><a href="https://docs.keypop.org/keypop-card-cpp-api/">C++ Doc</a></td>
			<td><a href="https://docs.terminal-api.calypsonet.org/card/">Specification</a></td>
		</tr>
		<tr>
			<th scope="row">Repository</th>
			<td><a href="https://github.com/eclipse-keypop/keypop-card-java-api">keypop-card-java-api</a></td>
			<td><a href="https://github.com/eclipse-keypop/keypop-card-cpp-api">keypop-card-cpp-api</a></td>
			<td><a href="https://github.com/calypsonet/calypsonet-terminal-card-api-spec">calypsonet-terminal-card-api-spec</a></td>
		</tr>
		<tr>
			<td rowspan="8">Card Layer - Calypso</td>
			<td rowspan="2">Calypso Card API</td>
			<th scope="row">API Doc</th>
			<td><a href="https://docs.keypop.org/keypop-calypso-card-java-api">Java Doc</a></td>
			<td><a href="https://docs.keypop.org/keypop-calypso-card-cpp-api">C++ Doc</a></td>
			<td><a href="https://docs.terminal-api.calypsonet.org/calypso-card/">Specification</a></td>
		</tr>
		<tr>
			<th scope="row">Repository</th>
			<td><a href="https://github.com/eclipse-keypop/keypop-calypso-card-java-api">keypop-calypso-card-java-api</a></td>
			<td><a href="https://github.com/eclipse-keypop/keypop-calypso-card-cpp-api">keypop-calypso-card-cpp-api</a></td>
			<td><a href="https://github.com/calypsonet/calypsonet-terminal-calypso-card-api-spec">calypsonet-terminal-calypso-card-api-spec</a></td>
		</tr>
		<tr>
			<td rowspan="2">Calypso Symmetric Crypto API</td>
			<th scope="row">API Doc</th>
			<td><a href="https://docs.keypop.org/keypop-calypso-crypto-symmetric-java-api/">Java Doc</a></td>
			<td><a href="https://docs.keypop.org/keypop-calypso-crypto-symmetric-cpp-api/">C++ Doc</a></td>
			<td><a href="https://docs.terminal-api.calypsonet.org/calypso-crypto-symmetric/">Specification</a></td>
		</tr>
		<tr>
			<th scope="row">Repository</th>
			<td><a href="https://github.com/eclipse-keypop/keypop-calypso-crypto-symmetric-java-api">keypop-calypso-crypto-symmetric-java-api</a></td>
			<td><a href="https://github.com/eclipse-keypop/keypop-calypso-crypto-symmetric-cpp-api">keypop-calypso-crypto-symmetric-cpp-api</a></td>
			<td><a href="https://github.com/calypsonet/calypsonet-terminal-calypso-crypto-symmetric-api-spec">calypsonet-terminal-calypso-crypto-symmetric-api-spec</a></td>
		</tr>
        <tr>
			<td rowspan="2">Calypso Legacy SAM Crypto API</td>
			<th scope="row">API Doc</th>
			<td><a href="https://docs.keypop.org/keypop-calypso-crypto-legacysam-java-api">Java Doc</a></td>
			<td><a href="https://docs.keypop.org/keypop-calypso-crypto-legacysam-cpp-api">C++ Doc</a></td>
			<td><a href="https://docs.terminal-api.calypsonet.org/calypso-crypto-legacysam/">Specification</a></td>
		</tr>
        <tr>
			<th scope="row">Repository</th>
			<td><a href="https://github.com/eclipse-keypop/keypop-calypso-crypto-legacysam-java-api">keypop-calypso-crypto-legacysam-java-api</a></td>
			<td><a href="https://github.com/eclipse-keypop/keypop-calypso-crypto-legacysam-cpp-api">keypop-calypso-crypto-legacysam-cpp-api</a></td>
			<td><a href="https://github.com/calypsonet/calypsonet-terminal-calypso-crypto-legacysam-api-spec">calypsonet-terminal-calypso-crypto-legacysam-api-spec</a></td>
		</tr>
        <tr>
			<td rowspan="2">Calypso Asymmetric Crypto API</td>
			<th scope="row">API Doc</th>
			<td><a href="https://docs.keypop.org/keypop-calypso-crypto-asymmetric-java-api">Java Doc</a></td>
			<td><a href="https://docs.keypop.org/keypop-calypso-crypto-asymmetric-cpp-api">C++ Doc</a></td>
			<td><a href="https://docs.terminal-api.calypsonet.org/calypso-crypto-asymmetric/">Specification</a></td>
		</tr>
        <tr>
			<th scope="row">Repository</th>
			<td><a href="https://github.com/eclipse-keypop/keypop-calypso-crypto-asymmetric-java-api">keypop-calypso-crypto-asymmetric-java-api</a></td>
			<td><a href="https://github.com/eclipse-keypop/keypop-calypso-crypto-asymmetric-cpp-api">keypop-calypso-crypto-asymmetric-cpp-api</a></td>
			<td><a href="https://github.com/calypsonet/calypsonet-terminal-calypso-crypto-asymmetric-api-spec">calypsonet-terminal-calypso-crypto-asymmetric-api-spec</a></td>
		</tr>
		<tr>
			<td rowspan="2">Card Layer - Storage Card</td>
			<td rowspan="2">Storage Card API</td>
			<th scope="row">API Doc</th>
			<td><a href="https://docs.keypop.org/keypop-storagecard-java-api/">Java Doc</a></td>
			<td style="border: 1px dotted #7D7D7D;"></td>
			<td><a href="https://docs.terminal-api.calypsonet.org/storagecard/">Specification</a></td>
		</tr>
		<tr>
			<th scope="row">Repository</th>
			<td><a href="https://github.com/eclipse-keypop/keypop-storagecard-java-api/">keypop-storagecard-java-api</a></td>
			<td style="border: 1px dotted #7D7D7D;"></td>
			<td><a href="https://github.com/calypsonet/calypsonet-terminal-storagecard-api-spec">calypsonet-terminal-storagecard-api-spec</a></td>
		</tr>
	</tbody>
</table>

## Keypop project support repositories

<table>
	<tbody>
		<tr>
			<th scope="col" colspan="2">Support type</th>
			<th scope="col">Repository</th>
		</tr>
		<tr>
			<td rowspan="2">Project websites</td>
			<td>main https://keypop.org/</td>
			<td><a href="https://github.com/eclipse-keypop/keypop-website">keypop-website</a></td>
		</tr>
		<tr>
			<td>API docs https://docs.keypop.org/</td>
			<td><a href="https://github.com/eclipse-keypop/keypop-api-docs">keypop-api-docs</a></td>
		</tr>
		<tr>
			<td rowspan="1">Continuous Integration</td>
			<td>GitHub Actions</td>
			<td><a href="https://github.com/eclipse-keypop/keypop-actions/">keypop-actions</a></td>
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


## Repositories of older, no-longer-maintained versions of Keypop

<table>
	<tbody>
		<tr>
			<th scope="col" colspan="2">$\text{\color{red}Deprecated}$ elements</th>
			<th scope="col">$\text{\color{red}Archived}$ repository</th>
		</tr>
		<tr>
			<td rowspan="1">Continuous integration</td>
			<td>Jenkins configuration</td>
			<td><a href="https://github.com/eclipse-keypop/keypop-ops/">keypop-ops</a></td>
		</tr>
	</tbody>
</table>