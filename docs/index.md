# Inicio

<div align="center">
	<a href="https://wureset.com/" target="_blank" rel="noopener noreferrer">
		<img src="https://brasil.wureset.com/assets/images/logo.png" alt="logo wureset" height="300" width="300">
	</a>
</div>
<br />

Esta ferramenta foi meticulosamente desenvolvida para atuar como um sólido suporte às opções de reparo do sistema. Ela oferece a capacidade de redefinir os componentes vitais do Windows Update, remover arquivos temporários, identificar e corrigir corrupções nas imagens do Windows, bem como verificar a integridade dos arquivos do sistema e substituir aqueles que estejam danificados. Além disso, ela possibilita a correção de valores inválidos no registro do Windows, a restauração das configurações do Winsock e diversas outras funcionalidades essenciais.

A ferramenta utilizada para redefinir os elementos do Windows Update opera por meio da linha de comando, entretanto, requer alguns requisitos fundamentais para seu funcionamento adequado. Estes incluem a compatibilidade com o sistema operacional em uso, bem como a execução com privilégios administrativos, entre outros.

Este documento foi elaborado com o propósito de fornecer uma descrição das etapas sequenciais necessárias para utilizar a ferramenta de redefinição do Windows Update de maneira adequada.

> ### Conteúdo
>
> [Requisitos](#requisitos) <br />
> [Glossário](#glossario) <br />
> [Referências](#referencias) <br />
> [Licença](#licenca)

## Requisitos

Esta ferramenta é plenamente compatível não apenas com o Windows 10, mas também com todas as versões posteriores desse sistema operacional.

Ao utilizar a ferramenta "Reset Windows Update", ela irá prontamente identificar a versão ou compilação do sistema operacional, e isso, por conseguinte, irá determinar tanto o nome quanto a família do sistema de forma automática.

Se o sistema operacional não for compatível com a ferramenta, uma mensagem de erro será apresentada e a ferramenta será automaticamente encerrada.

## Glossário

<dl>
<dt>DISM</dt>
<dd>Deployment Image Servicing and Management é uma ferramenta de linha de comando usada para montar e reparar imagens do Windows antes da implantação.</dd>
<dt>Fix It</dt>
<dd>É um programa de diagnóstico que permite detectar problemas que podem comprometer o bom funcionamento do Windows.</dd>
<dt>Registry</dt>
<dd>É um banco de dados hierárquico central introduzido no Microsoft Windows 95 e Windows NT para armazenar as informações necessárias para configurar o sistema para um ou mais usuários, aplicativos e dispositivos de hardware.</dd>
<dt>Restore point</dt>
<dd>é uma representação de um estado armazenado dos arquivos do sistema do computador.</dd>
<dt>SFC</dt>
<dd>System File Checker é um utilitário do Windows que permite aos usuários verificar corrupções nos arquivos de sistema do Windows e restaurar arquivos danificados.</dd>
<dt>Winsock</dt>
<dd>É uma biblioteca dinâmica de funções DLL para Windows, criada com a finalidade de implementar o TCP / IP. Inclui suporte para envio e recebimento de pacotes de dados através de soquetes BSD.</dd>
</dl>


## Referências

Como faço para redefinir os componentes do Windows Update?: [https://support.microsoft.com/pt-br/kb/971058](https://support.microsoft.com/pt-br/kb/971058).

Use a ferramenta Verificador de Arquivos do Sistema para reparar arquivos de sistema ausentes ou corrompidos: [https://support.microsoft.com/pt-br/kb/929833](https://support.microsoft.com/pt-br/kb/929833).

Corrigir erros do Windows Update usando o DISM ou a ferramenta de Preparação da Atualização do Sistema: [https://support.microsoft.com/pt-br/kb/947821](https://support.microsoft.com/pt-br/kb/947821).


## Licença

Reset Windows Update Tool está licenciada sob a licença MS-PL - consulte [Microsoft Public License](https://opensource.org/licenses/MS-PL) para obter mais detalhes.
