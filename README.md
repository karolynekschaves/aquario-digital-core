# 🌊 Missão: Sistema de Monitoramento e Controle de Qualidade Hídrica

Este repositório contém o sistema principal de avaliação e monitoramento da qualidade da água, responsável por analisar parâmetros vitais (como pH e Temperatura) e emitir alertas automatizados para a equipe ambiental.

---

## 🏗️ Arquitetura de Ambientes (Branches)

Nosso fluxo de trabalho segue a estrutura abaixo para garantir a integridade do código e a confiabilidade das análises:

*   **`develop` (Desenvolvimento):** Camada de integração contínua. É aqui que os desenvolvedores criam e testam novas funcionalidades (como novos sensores de turbidez ou oxigênio). Pode conter instabilidades.
*   **`stage` (Homologação):** Camada de testes finais e validação pelos biólogos. O ambiente é um espelho da produção, utilizado para simular dados reais das coletas antes da aprovação final.
*   **`main` (Produção):** Camada oficial e estável. Contém apenas o código que foi totalmente testado, validado e que está rodando ativamente no monitoramento dos tanques/reservatórios.

---

## 👥 Equipe Responsável

**Biólogos / Especialistas Ambientais:**
*   [Antonio 1] - Especialista em Ecologia Aquática
*   [Antonio 2] - Analista de Qualidade Hídrica

**Desenvolvedores / Engenharia de Software:**
*   [Karolyne S.] - Engenheiro de Software Responsável
*   [Karolyne S. - Desenvolvedor Backend

---