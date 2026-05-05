# DevHub

Plataforma colaborativa para desenvolvedores compartilharem projetos, fazer perguntas e respostas (Q&A), e conectar com outros desenvolvedores.

## Funcionalidades Principais

- **Feed Personalizado** - Veja posts dos desenvolvedores que você segue
- **Q&A** - Faça perguntas e receba respostas da comunidade
- **Projetos** - Publique e explore projetos open source
- **Grupos** - Crie e participe de grupos temáticos
- **Perfil** - Gerencie seu perfil e reputação
- **Notificações** - Receba notificações em tempo real

## Tech Stack

- Next.js 16 (App Router)
- TypeScript
- Tailwind CSS
- Supabase (Database + Auth + Realtime)
- OpenAI (busca semântica de duplicatas)

## Getting Started

```bash
npm install
npm run dev
```

## Estrutura do Projeto

```
app/
├── page.tsx          # Feed/Home
├── posts/            # Posts/Blog
├── questions/        # Q&A
├── projects/        # Projetos GitHub
├── groups/           # Grupos
├── profile/[id]/    # Perfil de usuário
└── notifications/  # Notificações
```

## Database

Entidades principais:
- `users` - Perfis de usuários
- `posts` - Publicações no feed
- `questions` - Perguntas Q&A
- `answers` - Respostas Q&A  
- `projects` - Projetos sincronizados
- `groups` - Grupos de desenvolvedores
- `votes` - Votações
- `badges` - Conquistas

## License

MIT