# Eclipse Keypop

This is the GitHub organization containing all repositories of the [Eclipse Keypop project](http://keypop.org/).

 - Keypop offers Java and C++ transcriptions of the '[Ticketing Terminal APIs](https://terminal-api.calypsonet.org/)' defined by the [Calypso Networks Association](https://calypsonet.org/).
 - The [Eclipse Keyple project](https://keyple.org/) provides Java and C++ libraries implementing the Keypop APIs.

## Keypop component repositories for Java and C++ implementations

<style>
    .hachured {
        background-image: repeating-linear-gradient(
        45deg,
        transparent,
        transparent 5px,
        rgba(0, 0, 0, 0.1) 5px,
        rgba(0, 0, 0, 0.1) 10px
        );
        color: black;
    }
</style>
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
			<td rowspan="6">Reader Layer</td>
			<td rowspan="3">Reader API</td>
			<th scope="row" rowspan="2">API Doc</th>
			<td rowspan="2"><a href="https://docs.keypop.org/keypop-reader-java-api">Java Doc</a></td>
			<td rowspan="2"><a href="https://docs.keypop.org/keypop-reader-cpp-api/">C++ Doc</a></td>
			<td><a href="https://docs.terminal-api.calypsonet.org/calypsonet-terminal-reader-uml-api/">UML Doc</a></td>
		</tr>
		<tr>
			<td><a href="https://terminal-api.calypsonet.org/specifications/reader-layer/reader-api/">Interface Guide</a></td>
        </tr>
		<tr>
			<th scope="row">Repository</th>
			<td><a href="https://github.com/eclipse-keypop/keypop-reader-java-api">keypop-reader-java-api</a></td>
			<td><a href="https://github.com/eclipse-keypop/keypop-reader-cpp-api">keypop-reader-cpp-api</a></td>
			<td><a href="https://calypsonet.github.io/calypsonet-terminal-reader-uml-api/">calypsonet-terminal-reader-uml-api</a></td>
		</tr>
		<tr>
			<td rowspan="3">Card API</td>
			<th scope="row" rowspan="2">API Doc</th>
			<td rowspan="2"><a href="https://docs.keypop.org/keypop-card-java-api/">Java Doc</a></td>
			<td rowspan="2"><a href="https://docs.keypop.org/keypop-reader-cpp-api/">C++ Doc</a></td>
			<td><a href="https://docs.terminal-api.calypsonet.org/calypsonet-terminal-card-uml-api/">UML Doc</a></td>
		</tr>
		<tr>
			<td><a href="https://terminal-api.calypsonet.org/specifications/reader-layer/card-api/">Interface Guide</a></td>
        </tr>
		<tr>
			<th scope="row">Repository</th>
			<td><a href="https://github.com/eclipse-keypop/keypop-card-java-api">keypop-card-java-api</a></td>
			<td><a href="https://github.com/eclipse-keypop/keypop-card-cpp-api">keypop-card-cpp-api</a></td>
			<td><a href="https://calypsonet.github.io/calypsonet-terminal-card-uml-api/">calypsonet-terminal-card-uml-api</a></td>
		</tr>
		<tr>
			<td rowspan="15">Card Layer - Calypso</td>
			<td rowspan="3">Calypso Card API</td>
			<th scope="row" rowspan="2">API Doc</th>
			<td rowspan="2"><a href="https://docs.keypop.org/keypop-calypso-card-java-api">Java Doc</a></td>
			<td rowspan="2"><a href="https://docs.keypop.org/keypop-calypso-card-cpp-api">C++ Doc</a></td>
			<td><a href="https://docs.terminal-api.calypsonet.org/calypsonet-terminal-calypso-card-uml-api/">UML Doc</a></td>
		</tr>
		<tr>
			<td><a href="https://terminal-api.calypsonet.org/specifications/calypso-layer/calypso-card-api/">Interface Guide</a></td>
        </tr>
		<tr>
			<th scope="row">Repository</th>
			<td><a href="https://github.com/eclipse-keypop/keypop-calypso-card-java-api">keypop-calypso-card-java-api</a></td>
			<td><a href="https://github.com/eclipse-keypop/keypop-calypso-card-cpp-api">keypop-calypso-card-cpp-api</a></td>
			<td><a href="https://calypsonet.github.io/calypsonet-terminal-calypso-uml-api/">calypsonet-terminal-calypso-card-uml-api</a></td>
		</tr>
		<tr>
			<td rowspan="3">Calypso Certificate API</td>
			<th scope="row" rowspan="2">API Doc</th>
			<td rowspan="2"></td>
			<td rowspan="2"></td>
			<td><a href="https://calypsonet.github.io/calypsonet-terminal-calypso-certificate-uml-api/">UML Doc</a></td>
		</tr>
		<tr>
            <td></td>
        </tr>
		<tr>
			<th scope="row">Repository</th>
			<td><a href="https://github.com/eclipse-keypop/keypop-calypso-certificate-java-api">keypop-calypso-certificate-java-api</a></td>
			<td><a href="https://github.com/eclipse-keypop/keypop-calypso-certificate-cpp-api">keypop-calypso-certificate-cpp-api</a></td>
			<td><a href="https://github.com/calypsonet/calypsonet-terminal-calypso-certificate-uml-api">calypsonet-terminal-calypso-certificate-uml-api</a></td>
		</tr>
		<tr>
			<td rowspan="3">Calypso Symmetric Crypto API</td>
			<th scope="row" rowspan="2">API Doc</th>
			<td rowspan="2"><a href="https://docs.keypop.org/keypop-calypso-crypto-legacysam-java-api">Java Doc</a></td>
			<td rowspan="2"><a href="https://docs.keypop.org/keypop-calypso-crypto-legacysam-cpp-api">C++ Doc</a></td>
			<td><a href="https://docs.terminal-api.calypsonet.org/calypsonet-terminal-calypso-crypto-symmetric-uml-api/">UML Doc</a></td>
		</tr>
		<tr>
			<td><a href="https://terminal-api.calypsonet.org/specifications/calypso-layer/calypso-symmetric-crypto-api/">Interface Guide</a></td>
        </tr>
		<tr>
			<th scope="row">Repository</th>
			<td><a href="https://github.com/eclipse-keypop/keypop-calypso-crypto-symmetric-java-api">keypop-calypso-crypto-symmetric-java-api</a></td>
			<td><a href="https://github.com/eclipse-keypop/keypop-calypso-crypto-symmetric-cpp-api">keypop-calypso-crypto-symmetric-cpp-api</a></td>
			<td><a href="https://github.com/calypsonet/calypsonet-terminal-calypso-crypto-symmetric-uml-api">calypsonet-terminal-calypso-crypto-symmetric-uml-api</a></td>
		</tr>
        <tr>
			<td rowspan="3">Calypso Legacy SAM Crypto API</td>
			<th scope="row" rowspan="2">API Doc</th>
			<td rowspan="2"><a href="https://docs.keypop.org/keypop-calypso-crypto-legacysam-java-api">Java Doc</a></td>
			<td rowspan="2"><a href="https://docs.keypop.org/keypop-calypso-crypto-legacysam-cpp-api">C++ Doc</a></td>
			<td><a href="https://docs.terminal-api.calypsonet.org/calypsonet-terminal-calypso-crypto-legacysam-uml-api/">UML Doc</a></td>
		</tr>
		<tr>
			<td><a href="https://terminal-api.calypsonet.org/specifications/calypso-layer/calypso-legacysam-api/">Interface Guide</a></td>
        </tr>
        <tr>
			<th scope="row">Repository</th>
			<td><a href="https://github.com/eclipse-keypop/keypop-calypso-crypto-legacysam-java-api">keypop-calypso-crypto-legacysam-java-api</a></td>
			<td><a href="https://github.com/eclipse-keypop/keypop-calypso-crypto-legacysam-cpp-api">keypop-calypso-crypto-legacysam-cpp-api</a></td>
			<td><a href="https://calypsonet.github.io/calypsonet-terminal-calypso-crypto-legacysam-uml-api/">calypsonet-terminal-calypso-crypto-legacysam-uml-api</a></td>
		</tr>
        <tr>
			<td rowspan="3">Calypso Asymmetric Crypto API</td>
			<th scope="row" rowspan="2">API Doc</th>
			<td rowspan="2"><a href="https://docs.keypop.org/keypop-calypso-crypto-asymmetric-java-api">Java Doc</a></td>
			<td rowspan="2"><a href="https://docs.keypop.org/keypop-calypso-crypto-asymmetric-cpp-api">C++ Doc</a></td>
			<td><a href="https://docs.terminal-api.calypsonet.org/calypsonet-terminal-calypso-crypto-asymmetric-uml-api/">UML Doc</a></td>
		</tr>
		<tr>
			<td><a href="https://terminal-api.calypsonet.org/specifications/calypso-layer/calypso-asymmetric-crypto-api/">Interface Guide</a></td>
        </tr>
        <tr>
			<th scope="row">Repository</th>
			<td><a href="https://github.com/eclipse-keypop/keypop-calypso-crypto-asymmetric-java-api">keypop-calypso-crypto-asymmetric-java-api</a></td>
			<td><a href="https://github.com/eclipse-keypop/keypop-calypso-crypto-asymmetric-cpp-api">keypop-calypso-crypto-asymmetric-cpp-api</a></td>
			<td><a href="https://github.com/calypsonet/calypsonet-terminal-calypso-crypto-asymmetric-uml-api">calypsonet-terminal-calypso-crypto-asymmetric-uml-api</a></td>
		</tr>
		<tr>
			<td rowspan="3">Card Layer - Storage Card</td>
			<td rowspan="3">Storage Card API</td>
			<th scope="row" rowspan="2">API Doc</th>
			<td rowspan="2"><a href="https://docs.keypop.org/keypop-storagecard-java-api/">Java Doc</a></td>
			<td rowspan="2" class="hachured"></td>
			<td><a href="https://docs.terminal-api.calypsonet.org/calypsonet-terminal-storagecard-uml-api/">UML Doc</a></td>
		</tr>
		<tr>
			<td><a href="https://terminal-api.calypsonet.org/specifications/card-layer-storagecard/storagecard-api/">Interface Guide</a></td>
        </tr>
		<tr>
			<th scope="row">Repository</th>
			<td><a href="https://github.com/eclipse-keypop/keypop-storagecard-java-api/">keypop-storagecard-java-api</a></td>
			<td class="hachured"></td>
			<td><a href="https://github.com/calypsonet/calypsonet-terminal-storagecard-uml-api/">calypsonet-terminal-storagecard-uml-api</a></td>
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