# MIUI Security Port Universal

Projeto Android independente com interface inspirada no MIUI Security. Não é um port oficial e não contém código, recursos proprietários ou serviços internos da Xiaomi.

## Compatibilidade
- Android 8.0 (API 26) ou superior como versão mínima declarada.
- A disponibilidade de cada atalho depende da versão Android e da personalização do fabricante.
- Compilação com SDK 35 e Java 17.

## Recursos implementados
- Painel com versão do Android e modelo do aparelho.
- Leitura do armazenamento total/livre.
- Leitura do nível de bateria.
- Limpeza do cache privado deste aplicativo.
- Lista de apps iniciáveis que o Android disponibiliza e atalho para detalhes de cada app.
- Atalhos para configurações do sistema, bateria, armazenamento e políticas de Não Perturbe.

## Limitações importantes
Um aplicativo comum não pode limpar o cache de outros apps, encerrar processos, controlar CPU/GPU, alterar permissões silenciosamente ou acessar APIs privadas da Xiaomi. Essas ações exigem privilégios de sistema, APIs do fabricante ou autorização explícita. Por isso, os atalhos abrem as telas oficiais do Android e a limpeza atua apenas nos arquivos deste app.

A declaração de compatibilidade não significa que todos os recursos sejam idênticos em todos os fabricantes. Teste em cada aparelho/versão.

## Compilar pelo GitHub
1. Crie um repositório e envie todos os arquivos desta pasta.
2. Abra **Actions** no GitHub.
3. Se necessário, habilite GitHub Actions.
4. Execute **Build Android APK** em **Run workflow**, ou faça um push.
5. Abra a execução concluída e baixe o artefato `MIUISecurityPort-debug`.
6. Extraia o ZIP do artefato; o APK será `app-debug.apk`.

## Instalação
Instale o APK no aparelho Android. Se solicitado, permita a instalação de apps da fonte usada para baixar o APK.
