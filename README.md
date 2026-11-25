# DevOps Pipeline C#

Projeto de estudo para praticar DevOps com uma aplicação em C#: testes automatizados, Docker e CI/CD com GitHub Actions.

## A aplicação
Programa de console em C# que diz se um número é **par** ou **ímpar**. A aplicação é simples de propósito: o foco do projeto é o pipeline ao redor dela.

## Como rodar
Requisitos: .NET 10 SDK.

```
dotnet run --project src/ParImpar
```

## Roadmap
- [x] Aplicação em C# (console)
- [ ] Testes com xUnit
- [ ] Dockerfile
- [ ] Workflow no GitHub Actions (build + testes)
- [ ] Publicação da imagem no GitHub Container Registry
- [ ] Deploy em VM Linux
- [ ] Monitoramento com Prometheus e Grafana

## Ambiente
Desenvolvido em uma VM Ubuntu 26.04 LTS (VirtualBox).
