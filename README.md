# Pitch: SafeEPI no Rio Innovation Week 2025  
**Data:** 12 a 15 de agosto de 2025 – **Local:** Pier Mauá, Rio de Janeiro  
**Trilha sugerida:** Governança / Empreendedorismo / Deep Tech (conforme foco em ética e tecnologia)  

---

## 1. Introdução poderosa  
> “Você sabia que, só em 2024, o Brasil registrou 724.228 acidentes de trabalho, segundo dados consolidados do e‑Social, INSS e Observatório SST (MPT+OIT), com crescimento de cerca de 11% sobre 2023?” :contentReference[oaicite:2]{index=2}  
A maioria (74,3 %) desses acidentes foi do tipo típico (no ambiente de trabalho), 24,6 % em trajetos, e apenas 1 % por doenças ocupacionais — revelando falhas na detecção e registro dessas condições.  
Mais de 61 % resultaram em afastamentos de até 15 dias, e 11,9 % em afastamentos superiores a 15 dias.  
Esses números representam impacto humano e econômico graves: estima-se que os acidentes e doenças ocupacionais custem anualmente cerca de 4 % do PIB (aproximadamente R$ 468 bi, PIB de R$ 11,7 tri em 2024).

---

## 2. Identificação do problema  
Por que estamos falando sobre EPI?  
Porque a ausência ou uso incorreto de Equipamentos de Proteção Individual é um fator determinante em muitos acidentes.  
E o problema não é só a ausência do EPI, mas a **falta de um sistema eficiente para garantir, rastrear e fiscalizar** seu uso real e validado.

---

## 3. Por que SafeEPI?  
### ✅ Diferenciais legais e tecnológicos  
- Há outros sistemas que efetuam entregas de EPI por biometria, mas o que o nosso se diferencia:  
  Primeiro, a maioria dos sistemas se apoia apenas na **NR 6** para a legalidade da entrega.  
  Nós vamos além: cada colaborador, ao ser cadastrado, ganha um **certificado digital de nível avançado**, equivalente a um certificado do governo.  
  Cada vez que uma entrega é validada com biometria digital ou facial, o sistema, ao gerar o comprovante da entrega, **assina com o certificado digital do colaborador**, garantindo ainda mais **legalidade jurídica** ao documento.  
  Assim, além da NR 6, o sistema se baseia na **Medida Provisória 2202** e na **Lei 14.103** para assegurar validade legal aos comprovantes emitidos.

### 📊 Inteligência de dados integrada ao dia a dia  
- Outro grande motivo para escolher a SafeEPI é o contexto de **inteligência de dados**: nosso sistema nasceu junto a consultores de SST e engenheiros, portanto compreendemos profundamente as dores do dia a dia — desde planejamento para serviços de temporada, empreitadas ou projeções anuais.  
- Com a inteligência de dados incorporada, o planejamento fica muito mais eficaz.

---

## 4. MVP com visão clara de evolução  
- O sistema é um **MVP**, e escolhemos a gestão de entrega de EPI como base para crescer.  
- Como todo MVP, chega uma hora que devemos escolher: **para onde expandir?** O mercado de SST (Saúde e Segurança do Trabalho) é vasto, com diversos caminhos possíveis de crescimento:  
  - **Integração com o eSocial** para sincronização automática de registros;  
  - **Funcionalidades para eleições de CIPA**, votações e gestão participativa da segurança;  
  - **Marketplace entre fornecedores de EPI e empresas**, agilizando o processo de compra com base em consumo real e compliance;  
  - **Educação e treinamento digital integrados** (cursos, reciclagens) ligados ao histórico de uso;  
  - **Gestão de riscos e incidentes**, permitindo cruzar dados de entrega de EPI com registros de acidentes;  
  - **Módulos de mindfulness e saúde ocupacional**, alinhados às tendências de bem-estar no trabalho.  
- Essas são direções estratégicas para onde o MVP SafeEPI pode escalar.

---

## 5. Arquitetura tecnológica  
- Backend: **Node.js + TypeScript**  
- Frontend: **React**  
- Armazenamento em **S3 da AWS**, hospedagem via containers (Docker/Kubernetes)  
- **Integração com leitores biométricos:** Hamster Pro 2 da SecuGen e Digital Persona 4500 — compatíveis com desktop e mobile  
- Plataforma web + **app React Native**, ideal para entregas de EPI em campo (via captura de biometria facial ou digital na rua ou obra)  

---

## 6. Modelo de negócio  
- **Planos mensais escalonáveis** por número de colaboradores e pelas modalidades/módulos contratados:  
  - Essentials (inclusão de biometria + certificados digitais)  
  - Analytics (inteligência de dados + painéis de indicadores)  
  - Compliance (integração eSocial, CIPA, marketplace  
  - Enterprise (treinamentos, gestão de riscos)  

---

## 7. Encerramento — Chamada à ação  
> “Imagine uma solução inteligente, orientada por dados e estrategicamente pensada que transforma a gestão de EPIs. SafeEPI já responde à exigência da NR 6, MP 2202 e Lei 14.103 — e entrega valor real ao prevenir acidentes e reduzir custos.  
Estamos buscando parceiros para testar módulos integrados com o eSocial, rodar pilotos com CIPA digital e integrar fornecedores. Se sua empresa busca segurança, eficiência e inovação alinhadas a **ética e impacto social**, venha conversar conosco!”

---

## 8. Visão alinhada ao tema RIW2025  
- O tema central do Rio Innovation Week 2025 é **“Um olhar através da ética”**, questionando como tecnologias (IA, automação, biotecnologia) podem promover inclusão, e não desigualdade :contentReference[oaicite:3]{index=3}  
- SafeEPI se posiciona exatamente como uma **tecnologia ética**, que promove segurança, compliance e justiça no ambiente de trabalho — respeitando direitos dos trabalhadores, gerando evidência legal e democratizando controle total com transparência.

---

## 📋 Resumo final  
| Elemento        | Destaque                                                                 |
|----------------|--------------------------------------------------------------------------|
| Problema       | Altíssimos índices de acidentes — falta de rastreabilidade e gestão de EPI |
| Solução        | Certificado digital + biometria + assinatura jurídica nos comprovantes     |
| MVP            | Entrega de EPIs com infraestrutura legal e inteligência de dados          |
| Crescimento    | eSocial, CIPA, marketplace, módulos de saúde e risco                      |
| Tecnologia     | Node/TypeScript, React, AWS, biometria, app mobile                       |
| Modelo         | SaaS escalável por plano e colaboradores                                  |
| Alinhamento RIW| Inovação ética, impacto social e digitalização da SST                     |

---

Muito obrigado!  
Estou aberto para discutir pilotos, parcerias e roadmap de crescimento.  
**SafeEPI: uma solução transformadora, orientada por dados e pensada para gerar segurança real no trabalho.**
