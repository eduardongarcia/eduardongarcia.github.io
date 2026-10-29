# Política de Privacidade — Candeia

**Última atualização:** 29 de outubro de 2026

A Candeia é um aplicativo de planos de leitura bíblica. Não exige conta ou login e armazena os planos pessoais e o progresso no próprio dispositivo.

## Dados armazenados localmente

- Planos criados ou importados, incluindo títulos, descrições, referências bíblicas e tags.
- Nomes das jornadas, datas de início e ajustes do calendário de leitura.
- Marcações, datas e histórico de conclusão das leituras, inclusive de jornadas finalizadas.
- Versículos diários armazenados em cache.
- Preferências de lembretes: ativação, horários e dias da semana.
- Preferências de exibição, como o estado recolhido das dicas de leitura.

Esses dados não são enviados ao desenvolvedor nem sincronizados com servidores da Candeia.

Os gráficos, a frequência de leitura e as estimativas de conclusão são calculados no próprio aparelho a partir das marcações. A estimativa utiliza o ritmo recente de leitura.

## Versículo diário

Quando há internet, o aplicativo consulta a [Bible API](https://bible-api.com/) para obter um versículo em português. Essa consulta não inclui os planos, os nomes das jornadas ou o histórico de leitura.

O provedor pode receber informações técnicas da conexão, como endereço IP e dados da requisição. A conexão utiliza HTTPS. O versículo obtido fica em cache para reutilização no mesmo dia. As verificações automáticas reutilizam o cache válido; ao puxar a tela inicial para atualizar, o usuário solicita uma nova consulta. Se a consulta falhar, o app mantém o versículo disponível ou utiliza a seleção incluída no aplicativo.

## Anúncios

A Candeia utiliza o Google AdMob para exibir anúncios. As solicitações de anúncios são configuradas como não personalizadas, mas o SDK pode coletar e compartilhar com o Google:

- Endereço IP, que pode indicar a localização aproximada.
- Interações com o aplicativo e com os anúncios.
- Informações de diagnóstico e desempenho.
- Identificadores do dispositivo ou da conta, como identificador de publicidade e App Set ID, quando aplicáveis.

Essas informações são utilizadas para veiculação e medição de anúncios, análise e prevenção de fraude. O Google informa que os dados são criptografados durante a transmissão por TLS.

O tratamento pelo Google segue a [Política de Privacidade do Google](https://policies.google.com/privacy). Consulte também as [informações de coleta de dados do Google Mobile Ads SDK](https://developers.google.com/admob/android/privacy/play-data-disclosure).

No Android, o aplicativo consulta a Plataforma de Mensagens de Usuários do Google (UMP) antes de solicitar anúncios e apresenta as mensagens de privacidade exigidas conforme a região e a configuração do serviço. Os anúncios só são solicitados quando o UMP permite. Quando exigido pelo Google, a opção **Privacidade dos anúncios**, no rodapé da tela inicial, permite revisar as escolhas.

Uma escolha contrária à personalização pode permitir outros modos de anúncio previstos pelo Google. Se o UMP não permitir solicitar anúncios, a área de publicidade permanece vazia. Essas escolhas não impedem o uso offline dos planos e do progresso e são distintas das permissões de notificações e de salvamento de imagens.

## Importação, exportação e compartilhamento

A importação de arquivos é realizada por escolha do usuário. O aplicativo permite exportar em JSON os planos criados ou importados pelo usuário, gerar PDFs de planos, copiar textos e compartilhar ou salvar cartões do plano, da jornada, da leitura diária e do versículo exibido.

O conteúdo pode incluir nomes de planos, referências bíblicas e progresso de leitura. O usuário escolhe o destino pelo menu do sistema. Ao escolher **Salvar imagem**, o cartão é adicionado à galeria do aparelho. A Candeia não envia automaticamente esses arquivos a terceiros.

As cópias de segurança exportadas incluem os planos pessoais e as jornadas, com suas marcações e ajustes de calendário. A restauração é iniciada pelo usuário; não há backup automático em servidores da Candeia. O cache de versículos e as preferências de lembretes não integram essas cópias.

**A restauração substitui os planos pessoais e todas as jornadas existentes no aparelho pelos dados do backup, sem mesclagem.** Planos pessoais, jornadas e marcações que não estejam no arquivo, inclusive alterações posteriores à sua criação, não são preservados. Antes de restaurar, exporte uma cópia dos dados atuais se desejar guardá-los.

Cada jornada inclui uma cópia do plano usado ao iniciá-la, mesmo quando ele é fornecido com o aplicativo. Essa cópia permanece vinculada à jornada e não cria um plano adicional na biblioteca. Se o plano original tiver sido atualizado ou removido da biblioteca, a jornada restaurada mantém as leituras e marcações salvas no backup. A restauração não substitui os planos incluídos na versão atual do app nem recoloca na biblioteca um plano removido que exista apenas na cópia de uma jornada. Planos criados ou importados pelo usuário voltam à biblioteca quando constam na lista de planos pessoais do backup.

Quando você envia ou salva um arquivo em outro aplicativo ou serviço, o tratamento desse conteúdo segue as políticas do destino escolhido.

## Permissões

Os recursos de seleção, salvamento e compartilhamento de arquivos do sistema são utilizados quando o usuário solicita essas ações. O aplicativo não utiliza localização precisa para organizar as leituras.

Ao salvar um cartão, o aplicativo solicita somente o acesso necessário para adicionar a imagem à galeria, quando exigido pelo sistema. Não solicita leitura da galeria nem utiliza as fotos existentes. Em versões antigas do Android, pode ser necessária a permissão de gravação no armazenamento.

A permissão de notificações é solicitada ao ativar os lembretes de leitura. Os lembretes são agendados no próprio aparelho, sem envio de horários ou preferências a servidores e sem notificações remotas. Você pode desativá-los no aplicativo ou nas configurações do sistema. Essas preferências não fazem parte das cópias de segurança das jornadas.

## Retenção e exclusão de dados

Os dados locais permanecem no dispositivo até serem excluídos pelo usuário, pela limpeza dos dados do aplicativo nas configurações do sistema ou pela desinstalação.

Cópias de segurança, PDFs e imagens exportados devem ser excluídos separadamente dos locais onde foram salvos ou compartilhados.

A retenção e a exclusão de informações recebidas pelo Google ou pela Bible API seguem as políticas e os mecanismos desses provedores. Limpar ou desinstalar a Candeia não exclui dados mantidos por terceiros.

## Alterações

Esta política pode ser atualizada para refletir mudanças nas funcionalidades ou nos serviços utilizados. A data da última atualização será indicada no início do documento.

## Contato

Para dúvidas ou solicitações sobre privacidade, utilize o e-mail disponibilizado na seção **Contato do desenvolvedor** da ficha oficial da Candeia no Google Play.
