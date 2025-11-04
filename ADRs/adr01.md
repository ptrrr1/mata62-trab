# ADR01: Arquitetura 'Event-Driven' para satisfazer aspectos arquiteturais

Autor: Pedro H Costa

## Status

**Status:** Aprovado \
**Data:** 23-10-2025

## Contexto

O conjunto de aspectos arquiteturais ditos necessários (Resiliência, Modularidade e Elasticidade) necessitavam de uma arquitetura em que os módulos fossem independentes e pudessem ser ditribuídos em escala sob demanada.

## Decisão

A Arquitetura baseada em eventos (Event-Driven) possui baixo acoplamento entre as partes (Modularidade) e permite manter inúmeras instâncias simultâneas de um mesmo consumidor (Elasticidade e Resiliência) de maneira simples.
