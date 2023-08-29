# Redefinir componentes

Caso você esteja lidando com problemas persistentes envolvendo o Windows Update, poderá ser essencial restaurar os componentes do Windows Update às suas configurações padrão. Essa ferramenta foi minuciosamente desenvolvida com o propósito de resolver questões vinculadas a tais componentes.

> ### Conteúdo
>
> [Redefinir componentes do Windows Update](#redefinir-componentes-do-windows-update) <br />
> [Não foi possível parar o serviço de atualização do Windows](#não-foi-possível-parar-o-serviço-de-atualização-do-windows)

## Redefinir componentes do Windows Update

Antes de prosseguir, é importante criar um backup do registro para o caso de algo dar errado durante o processo.

Para redefinir os componentes do Windows Update para seus valores padrão, selecione a opção "Reset Windows Update components" (Redefinir componentes do Windows Update). Isso interromperá os serviços do Windows Update e limpará os componentes, restaurando-os para suas configurações iniciais.

A ferramenta começará a redefinir os componentes automaticamente e o processo deverá ser concluído em alguns minutos.

Depois de concluído, é recomendável instalar o Windows Update Agent mais recente a partir do seguinte link: [https://support.microsoft.com/pt-br/kb/949104](https://support.microsoft.com/pt-br/kb/949104).

Por fim, reinicie o computador para salvar as alterações.

## O serviço Windows Update não pôde ser interrompido

Se o Windows Update Service não for interrompido, execute essa ferramenta no modo de segurança.

<div align="center">
	<img src="https://brasil.wureset.com/assets/images/failed.png" alt="failed command">
</div>
<br />

Para acessar o modo de segurança, você pode entrar no ambiente de recuperação do Windows mantendo pressionada a tecla Shift enquanto clica em Reiniciar. Isso o levará ao menu Advanced Boot Options (Opções avançadas de inicialização), onde você poderá selecionar o Modo de segurança.

Se o erro continuar ocorrendo, é possível que a instalação do Windows esteja em mau estado e precise ser reparada ou reinstalada.
