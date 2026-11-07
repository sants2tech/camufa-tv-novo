# Camufa TV novo

Cópia independente do KamuflaTV original, preservando o layout e os recursos de navegação para Smart TV, canais ao vivo, filmes, séries, favoritos, histórico, último canal assistido e EPG.

## Configuração inicial

Ao abrir o aplicativo, informe:

- URL do servidor Xtream (por exemplo, `https://servidor.exemplo.com:8080`);
- usuário;
- senha;
- URL do EPG em XMLTV.

Não há usuário, senha ou URL de API privada embutidos no código. A configuração pode ser salva apenas no dispositivo/navegador atual ou mantida somente durante a sessão.

## Conteúdos adultos

Categorias com nomes como `adult`, `adulto`, `18+`, `xxx`, `porn`, `erótico`, `sexo` e termos relacionados aparecem no catálogo por padrão, conforme solicitado. O controle parental do aplicativo continua disponível para bloquear categorias ou itens manualmente.

## Persistência local

O navegador mantém favoritos, histórico de filmes/séries, progresso de reprodução e o último canal assistido usando `localStorage`. Nenhum desses dados é enviado por este projeto para um serviço próprio.

## Observação sobre CORS

O servidor Xtream e a URL do EPG precisam aceitar requisições do domínio em que o aplicativo estiver hospedado. Se o provedor bloquear CORS, será necessário usar um proxy autorizado pelo proprietário do serviço.
