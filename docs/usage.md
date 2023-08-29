# Uso

A ferramenta "Windows Update Reset" utiliza funcionalidades de linha de comando para executar seus processos. É crucial notar que certas funções de restauração podem não se encontrar disponíveis em todas as edições do Windows. A ferramenta identificará essas limitações para mitigar possíveis erros.

Para aplicar as correções requeridas, simplesmente insira o número associado à função desejada e pressione a tecla "Enter".

> ### Conteúdo
>
> [Executar como administrador](#executar-como-administrador) <br />
> [Linha de comando](#linha-de-comando)

## Executar como administrador

**User Account Control** (UAC) é um recurso obrigatório de controle de acesso introduzido nos sistemas operacionais Windows Vista e Windows Server 2008 da Microsoft, com uma versão mais descontraída também presente no Windows 7, Windows Server 2008 R2, Windows 8, Windows Server 2012 e Windows 10. Seu objetivo é melhorar a segurança do Microsoft Windows, limitando o software do aplicativo a privilégios de usuário padrão até que um administrador autorize um aumento ou elevação. Dessa maneira, somente aplicativos confiáveis ​​do usuário podem receber privilégios administrativos, e o malware deve ser impedido de comprometer o sistema operacional. Em outras palavras, uma conta de usuário pode ter privilégios de administrador atribuídos, mas os aplicativos que o usuário executa não herdam esses privilégios, a menos que sejam aprovados previamente ou explicitamente autorizados pelo usuário.

### Como executar um programa como administrador

Para executar um programa como administrador, siga estas etapas:

1. Clique no ícone usado para executar o programa e clique em **Executar como administrador**.
2. Quando for solicitada uma senha ou confirmação de administrador, digite a senha do administrador ou clique em **continuar**.

Para alguns ícones de programa, a opção **Executar como administrador** não está disponível no menu de contexto. Para esses ícones de programa, siga estas etapas:

1. Clique no ícone usado para executar o programa e clique em **Propriedades**. Na guia **atalho** da caixa **destino** contém o local e o nome do arquivo do programa.
2. Abra a pasta que contém o arquivo de programa.
3. Clique no arquivo do programa e clique em **Executar como administrador**. Se você for solicitado uma senha de administrador ou confirmação, digite a senha ou clique em **continuar**.

Se você precisar executar um programa como administrador, é aconselhável configurá-lo para ser executado automaticamente como administrador. Para fazer isso, execute as seguintes etapas:

1. Clique no ícone usado para executar o programa e clique em **Propriedades**.
2. Na guia **compatibilidade**, clique para selecionar a caixa de seleção **execute este programa como administrador** e clique em **OK**.

A guia **compatibilidade** não está disponível para alguns ícones de programa. Para esses ícones de programa, siga estas etapas:

1. Clique no ícone usado para executar o programa e clique em **Propriedades**. Na guia **atalho** da caixa **destino** contém o local e o nome do arquivo do programa.
2. Abra a pasta que contém o arquivo de programa.
3. Clique no arquivo do programa e clique em **Propriedades**.
4. Na guia **compatibilidade**, clique para selecionar a caixa de seleção **execute este programa como administrador** e clique em **OK**.

<div align="center">
	<img src="https://brasil.wureset.com/assets/images/runas.gif" alt="contextual menu run as an admin">
</div>
<br />

Para mais informações, consulte a [referência](https://support.microsoft.com/pt-br/kb/922708)

## Linha de comando

Reset Windows Update Tool pode ser usado na linha de comando da seguinte maneira:

```
$ WURESET [/reset][/search][/clean:{temp|regs|sock}][/sfc][/dism:{scan|check|repair|clean}]
```

Aqui estão listadas entre parênteses as várias opções que podem ser usadas com a ferramenta. Essas opções incluem reiniciar a ferramenta, verificar se há atualizações, limpar arquivos temporários ou valores de registro, executar o Verificador de arquivos do sistema (SFC) e executar o DISM para verificar, reparar ou limpar a imagem do sistema.

**Lista de Parâmetros**

<table border="0" cellpadding="4">
	<tr>
		<th>
			Parâmetro
		</th>
		<th>
			Descrição
		</th>
		<th>
			Abreviação
		</th>
		<th>
			Exemplo
		</th>
	</tr>
	<tr>
		<td>
			reset
		</td>
		<td>
			Redefina os componentes do Windows Update.
		</td>
		<td>
		</td>
		<td>
			/reset <br />
			-reset
		</td>
	</tr>
	<tr>
		<td>
			search
		</td>
		<td>
			Verifique se há atualizações.
		</td>
		<td>
		</td>
		<td>
			/search <br />
			-search
		</td>
	</tr>
	<tr>
		<td>
			clean
		</td>
		<td>
			Opções de limpeza.
		</td>
		<td>
		</td>
		<td>
			/clean:temp <br />
			/clean:regs:temp <br />
			-clean:temp <br />
			-clean:sock
		</td>
	</tr>
	<tr>
		<td>
			sfc
		</td>
		<td>
			Examine todos os arquivos protegidos do sistema.
		</td>
		<td>
		</td>
		<td>
			/sfc <br />
			-sfc
		</td>
	</tr>
	<tr>
		<td>
			dism
		</td>
		<td>
			Opções do DISM.
		</td>
		<td>
		</td>
		<td>
			/dism:scan:repair:clean <br />
			-dism:check:repair
		</td>
	</tr>
	<tr>
		<td>
			help
		</td>
		<td>
			Mostre uma mensagem de ajuda.
		</td>
		<td>
			<b>h</b> o <b>?</b>
		</td>
		<td>
			/help <br />
			/h <br />
			/? <br />
			-help <br />
			-h <br />
			-?
		</td>
	</tr>
	<tr>
		<td>
			version
		</td>
		<td>
			Mostra uma mensagem de versão.
		</td>
		<td>
			<b>v</b>
		</td>
		<td>
			/version <br />
			/v <br />
			-version <br />
			-v
		</td>
	</tr>
</table>

**Amostra de uso:**

<div>
	<img src="https://brasil.wureset.com/assets/images/commands.gif" alt="example of command line">
</div>
<br />

Para verificar a versão

<div>
	<img src="https://brasil.wureset.com/assets/images/version.gif" alt="get version with command line">
</div>
<br />
