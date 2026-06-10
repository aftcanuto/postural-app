# Avaliação Postural — MedFit

App de avaliação postural clínica com simetrógrafo, landmarks anatômicos e checklist por planos.

## Como fazer o deploy no GitHub Pages

### 1. Criar repositório no GitHub
- Acesse github.com → New repository
- Nome: `postural-app`
- Visibilidade: **Private** (recomendado para dados clínicos)
- Clique em **Create repository**

### 2. Fazer upload do arquivo
- No repositório criado, clique em **Add file → Upload files**
- Arraste o `index.html` para a área de upload
- Clique em **Commit changes**

### 3. Ativar GitHub Pages
- Vá em **Settings → Pages**
- Em "Branch", selecione `main` e pasta `/root`
- Clique em **Save**
- Aguarde ~1 min e acesse: `https://aftcanuto.github.io/postural-app`

## Funcionalidades

1. **Paciente** — identificação completa, cálculo automático de IMC e idade, anamnese rápida
2. **Fotos** — carregamento das 4 vistas posturais (anterior, posterior, laterais)
3. **Simetrógrafo** — eixo vertical + 6 linhas horizontais anatômicas ajustáveis, cores e espessura configuráveis
4. **Landmarks** — marcação de pontos anatômicos com nome, medição de ângulos entre 3 pontos
5. **Achados** — checklist clínico completo por plano frontal e sagital com lateralidade, campo de conclusão e conduta
6. **Exportar** — fotos em resolução original com simetrógrafo + landmarks + ângulos desenhados

## Próximas versões planejadas
- [ ] Laudo PDF completo
- [ ] Evolução longitudinal (comparativo antes/depois)
- [ ] Integração com Diagnóstico Fisiometabólico
