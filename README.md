# MUTARENA 4.0

Jogo PWA de criação de feras mutantes, Bestiário e batalhas automáticas.

## Publicação oficial no GitHub Pages

1. Crie um repositório público `Shauell/-mutarena`.
2. Envie todo o conteúdo desta pasta para a branch `lua`.
3. No GitHub, abra **Settings → Pages**.
4. Em **Build and deployment**, selecione **GitHub Actions**.
5. A automação executará os testes e publicará o jogo.

Depois da primeira publicação, toda alteração enviada à branch `lua` será testada e publicada no mesmo endereço.

## Instalar no iPhone

Abra o endereço publicado no Safari e toque em **Compartilhar → Adicionar à Tela de Início**. O mesmo atalho continuará funcionando após futuras atualizações.

## Atualizações

Quando uma versão nova estiver disponível, o jogo mostrará **Nova mutação disponível**. O botão **Atualizar agora** ativa a nova versão e recarrega o aplicativo. O Bestiário permanece no armazenamento do navegador.

## Testes locais

- `npm test` executa os testes automatizados.
- `npm start` abre um servidor local em `http://localhost:4173`.

## Backup

No Bestiário, use **Exportar** para baixar um arquivo JSON. O botão **Importar** restaura esse arquivo depois de confirmação.

## Endereço previsto

Após a ativação do GitHub Pages, o jogo será publicado em `https://shauell.github.io/-mutarena/`.
