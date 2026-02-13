name: "🏗️ Nova Dor de Cliente"
description: Cadastrar uma demanda real para ser resolvida pelos alunos.
title: "[PROJETO]: "
labels: ["tipo: demanda-real", "status: triagem"]
body:
  - type: markdown
    attributes:
      value: |
        ### Bem-vindo à Recife Labs!
        Preencha os detalhes abaixo para que nossos talentos possam transformar sua dor em solução.
  - type: input
    id: empresa
    attributes:
      label: Nome da Empresa/Entidade
      placeholder: Ex: Padaria do Sr. João ou ONG Local
    validations:
      required: true
  - type: textarea
    id: dor
    attributes:
      label: Qual é o problema atual?
      placeholder: Descreva o que não está funcionando ou o que precisa ser criado.
    validations:
      required: true
  - type: dropdown
    id: categoria
    attributes:
      label: Categoria da Solução
      options:
        - Web (Site/Landing Page)
        - Automação IoT (ESP32/Sensores)
        - Gestão/RH (Processos)
        - Banco de Dados/API
    validations:
      required: true