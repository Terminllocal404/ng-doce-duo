# NG Doce Duo — Estrutura do Projeto

Esta pasta define a arquitetura-base do projeto. O proprietário adiciona os materiais visuais em `assets/`. O desenvolvedor deve implementar as funcionalidades respeitando esta organização.

## Conteúdo
- `assets/`: fotos, vídeos, logos e ícones fornecidos pelo proprietário.
- `pages/`: páginas da aplicação, separadas por área.
- `css/`: estilos globais e estilos específicos.
- `js/`: componentes, serviços e lógica JavaScript.
- `backend/`: implementação do servidor/API.
- `database/`: migrations e seeds.
- `docs/`: documentação, requisitos, arquitetura e auditorias.

## Regras para o desenvolvedor
1. Não mover, excluir ou renomear pastas estruturais sem autorização do proprietário.
2. Não colocar senhas, tokens ou chaves privadas no repositório.
3. Usar `.env` para segredos e manter apenas `.env.example` versionado.
4. Novas funcionalidades devem seguir a organização existente.
5. Alterações importantes devem ser feitas em branches e integradas por Pull Request.

## Conteúdo visual
- `assets/logo/`: logotipos.
- `assets/products/`: fotos dos produtos.
- `assets/images/`: demais imagens do site.
- `assets/videos/`: vídeos.
- `assets/icons/`: ícones.
