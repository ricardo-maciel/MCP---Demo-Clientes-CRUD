# 🚀 MCP Bridge Demo - Clientes CRUD (MuleSoft)

Repositório de estudo e compartilhamento para demonstrar, na prática, como expor APIs REST do MuleSoft/Anypoint Platform como ferramentas MCP usando **Omni Gateway** + **MCP Bridge**.

## 📚 Conteúdos em HTML (comece por aqui)

> **1️⃣ Primeiro — entenda o contexto:**  
> 📖 [A História do MCP — do isolamento dos AIs ao protocolo universal](https://ricardo-maciel.github.io/MCP---Demo-Clientes-CRUD/historia-do-mcp.html)

> **2️⃣ Depois — mão na massa:**  
> 🌐 [MCP Bridge & Omni Gateway — Manual Técnico](https://ricardo-maciel.github.io/MCP---Demo-Clientes-CRUD/mcp-bridge-manual.html)

## 🎯 Finalidade do repositório

Este repositório foi criado para permitir que outros desenvolvedores possam:

- 🔁 replicar o cenário completo de ponta a ponta;
- 🧩 estudar a configuração de **Omni Gateway** no Runtime Manager;
- 🛠️ entender o fluxo de criação do **MCP Bridge** no API Manager;
- 🤖 observar o mapeamento de endpoints REST para **tools MCP**;
- 🧪 usar uma base prática para testes, labs e aprendizado em times.

## 📦 O que você encontra neste repositório

- 📖 **História do MCP** (HTML) — origem, necessidades e evolução do protocolo;
- 📄 **Manual técnico em HTML** com o passo a passo completo;
- 🧾 **RAML de exemplo** da API utilizada no cenário;
- ☕ **Artefato `.jar`** da aplicação API criada no Anypoint Studio;
- 🗂️ arquivos auxiliares para facilitar compartilhamento e reprodução do ambiente.

## 🧭 Cenário abordado

O estudo cobre os principais pontos:

1. ✅ Preparação da API REST (Design Center / Exchange / CloudHub / API Manager);
2. ✅ Criação e provisionamento do **Omni Gateway**;
3. ✅ Configuração guiada do **MCP Bridge**:
   - Runtime
   - APIs
   - Downstream
   - Upstream
   - MCP Tools and Mapping
4. ✅ Resultado final com publicação de asset MCP e tools no Exchange;
5. 🔐 Boas práticas de segurança e governança (rate limit, client enforcement, exposição mínima etc.).

## 🔮 Futuras atualizações (roadmap)

Este repositório receberá novas evoluções com foco prático, incluindo:

- 🏗️ criação de APIs do zero até o deploy completo;
- ☁️ cenários de deploy em **CloudHub 1.0** e **CloudHub 2.0** para uso via **MCP Bridge**;
- 🧠 criação de **App MCP Server**;
- 🔌 uso de **conectores MCP** dentro dos fluxos Mule;
- 🤝 configuração e uso de MCP Server nas principais IAs/ferramentas do mercado:
  - 🖥️ **Cursor**
  - 📮 **Postman**
  - 💬 **Claude**
  - ⚡ **Agentforce**

## 👥 Público-alvo

- Desenvolvedores MuleSoft;
- Arquitetos e integradores de APIs;
- Times que estão avaliando integração entre APIs REST e agentes de IA via MCP.

## 📝 Observações

Este repositório tem foco educacional/demonstrativo.  
Adapte políticas de segurança, autenticação e limites de consumo antes de usar em produção.
