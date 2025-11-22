# Portfólio de QA – Akross

![Banner do portfólio](https://raw.githubusercontent.com/jeff-barbosa123/portfolio-qa-akross/main/banner-qa-jefferson-paulo.png)

Portfólio completo de Qualidade para a solução Akross, cobrindo risco, acessibilidade (WCAG 2.1 AA), usabilidade e conformidade. Inclui plano de testes, matriz de risco, auditoria técnica, evidências em vídeo e recomendações acionáveis.

## Índice
- [Visão Geral](#visão-geral)
- [Destaques](#destaques)
- [Entregáveis](#entregáveis)
- [Demonstração](#demonstração)
- [Links Rápidos](#links-rápidos)
- [Guia Rápido](#guia-rápido)
- [Metodologia e Critérios](#metodologia-e-critérios)
- [Ferramentas](#ferramentas)
- [Estrutura](#estrutura)
- [Publicação (inclui vídeos)](#publicação-inclui-vídeos)
- [Contato](#contato)

## Visão Geral
- Objetivo: aplicar práticas de QA ao produto Akross com foco em risco, acessibilidade e experiência do usuário.
- Papel: QA responsável por planejamento, execução, evidências e síntese executiva.
- Escopo: testes funcionais, análise de risco, checklist manual WCAG e auditoria técnica.
- Público: times de produto/engenharia e stakeholders que precisam de visibilidade de qualidade.

## Destaques
- Fluxo crítico validado e registrado em vídeo completo + versão compacta.
- Matriz de riscos priorizada para decisões rápidas.
- Auditoria com achados, severidade e recomendações objetivas.
- Checklist manual de acessibilidade (WCAG) com apontamentos e próximas ações.

## Entregáveis
- **Plano e Estratégia de Testes**: `Plano_e_Estrategia_de_Testes_Adaptada_Akoss.docx`
- **Foco Corporativo** (briefing/objetivos): `Foco_Corporativo_Akoss.docx`
- **Estudo de Acessibilidade Manual**: `estudo-acessibilidade-manual.docx`
- **Relatório de Auditoria**: `Relatario_de_Auditoria_Akoss.docx`
- **Tabela de Riscos**: `Tabela_de_Riscos_Akross.xlsx`
- **Evidência em vídeo (compacta)**: `evidencia_mAFP0cta.mp4`
- **Evidência em vídeo (completa)**: `lighthouse.mp4`
- **Evidência de ferramenta (Axe)**: `AxeDevTools.mp4`

## Demonstração
- Vídeo compacto: [evidencia_mAFP0cta.mp4](evidencia_mAFP0cta.mp4)  
- Vídeo completo: [lighthouse.mp4](lighthouse.mp4)  
- Evidência Axe: [AxeDevTools.mp4](AxeDevTools.mp4)

## Links Rápidos
- Vídeo compacto: [evidencia_mAFP0cta.mp4](evidencia_mAFP0cta.mp4)
- Vídeo completo: [lighthouse.mp4](lighthouse.mp4)
- Evidência Axe: [AxeDevTools.mp4](AxeDevTools.mp4)

## Guia Rápido
1) Assista `evidencia_mAFP0cta.mp4` (ou `lighthouse.mp4` para o fluxo completo; `AxeDevTools.mp4` para evidência de ferramenta).  
2) Leia `Plano_e_Estrategia_de_Testes_Adaptada_Akoss.docx` para escopo e critérios de aceite.  
3) Revise `Tabela_de_Riscos_Akross.xlsx` para a priorização aplicada.  
4) Consulte `Relatario_de_Auditoria_Akoss.docx` e `estudo-acessibilidade-manual.docx` para achados e recomendações.  
5) Use os vídeos acima para uma visão rápida do fluxo validado.

## Metodologia e Critérios
- Baseado em risco: foco em fluxos críticos e alto impacto.
- Acessibilidade: checklist manual (WCAG 2.1 AA) com contraste, navegação por teclado e rótulos.
- Evidências: gravação contínua e versionada.
- Comunicação: achados com severidade + recomendação acionável por entregável.

## Ferramentas
- Documentação: Word, Excel.
- Evidências: ffmpeg portátil (`tools/ffmpeg`) e ScreenToGif.
- Versionamento: GitHub.

## Estrutura
```
portfolio-qa-akross/
├─ docs/                         # assets públicos
├─ tools/ffmpeg/                 # ffmpeg portátil
├─ evidencia_mAFP0cta.mp4        # vídeo compacto
├─ lighthouse.mp4                # vídeo completo
├─ AxeDevTools.mp4               # evidência complementar (Axe)
├─ banner-qa-jefferson-paulo.png
├─ Plano_e_Estrategia_de_Testes_Adaptada_Akoss.docx
├─ Foco_Corporativo_Akoss.docx
├─ estudo-acessibilidade-manual.docx
├─ Relatario_de_Auditoria_Akoss.docx
└─ Tabela_de_Riscos_Akross.xlsx
```

## Publicação (inclui vídeos)
1. **Organize os binários**: MP4 em `./` (`evidencia_mAFP0cta.mp4`, `lighthouse.mp4`, `AxeDevTools.mp4`).  
2. **Git LFS (opcional para vídeos maiores)**:  
   - `git lfs track "*.mp4"` e confirme que `.gitattributes` inclui `*.mp4 filter=lfs`.  
3. **Commit** (exemplo):  
   - `git add README.md evidencia_mAFP0cta.mp4 lighthouse.mp4 AxeDevTools.mp4`  
   - `git commit -m "docs: publicar evidências em vídeo (compacto, completo e Axe)"`  
4. **Push**: `git push origin main` (ou o branch em uso).  
5. **Verifique no GitHub** se os links de download dos vídeos e documentos abrem corretamente no repositório público.

## Contato
- Jefferson Paulo — [LinkedIn](https://www.linkedin.com/) | jefferson.p.barbosa23@gmail.com
