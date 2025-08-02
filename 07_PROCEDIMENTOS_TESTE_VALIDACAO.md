# PROCEDIMENTOS DE TESTE E VALIDAÇÃO
## Adaptação Roda Traseira MT-07 em Yamaha R3 2021

---

## 1. PROTOCOLO GERAL DE TESTES

### 1.1 OBJETIVOS DOS TESTES
```
VALIDAR:
□ Integridade estrutural dos componentes
□ Funcionamento correto do sistema de freio
□ Alinhamento e balanceamento da roda
□ Ausência de interferências mecânicas
□ Comportamento dinâmico adequado
□ Segurança operacional

VERIFICAR:
□ Conformidade com cálculos de engenharia
□ Atendimento aos fatores de segurança
□ Durabilidade estimada dos componentes
□ Funcionalidade em condições extremas
```

### 1.2 FASES DE TESTE
```
FASE 1: Testes Estáticos (bancada)
FASE 2: Testes Dinâmicos Controlados (elevada)
FASE 3: Testes Funcionais (baixa velocidade)
FASE 4: Testes de Performance (velocidade normal)
FASE 5: Testes de Durabilidade (longo prazo)
```

---

## 2. FASE 1 - TESTES ESTÁTICOS

### 2.1 PREPARAÇÃO PARA TESTES

#### EQUIPAMENTOS NECESSÁRIOS
```
□ Cavalete traseiro robusto
□ Manômetro 0-10 bar (sistema freio)
□ Paquímetro digital 0.01mm
□ Relógio comparador 0.01mm
□ Torquímetro calibrado 10-150 Nm
□ Termômetro infravermelho
□ Balança 0-200kg
□ Gabarito alinhamento corrente
```

#### CONDIÇÕES AMBIENTAIS
```
Temperatura: 20 ± 5°C
Umidade: 45-65%
Pressão atmosférica: Normal
Local: Oficina fechada, piso nivelado
Iluminação: Mínimo 500 lux
```

### 2.2 TESTE 1: VERIFICAÇÃO DIMENSIONAL

#### PROCEDIMENTO
```
1. Elevar moto com cavalete traseiro
2. Remover corrente temporariamente
3. Medir batimento radial da roda:
   - Posicionar relógio comparador no pneu
   - Girar roda 360° manualmente
   - Anotar leitura máxima e mínima
   - LIMITE: ≤ 0.8mm total

4. Medir batimento lateral da roda:
   - Posicionar relógio na lateral do aro
   - Girar roda 360° manualmente
   - Anotar leitura máxima e mínima
   - LIMITE: ≤ 0.5mm total

5. Verificar centragem na balança:
   - Medir distância roda-balança (ambos lados)
   - Diferença máxima: 2mm
```

#### REGISTRO DE RESULTADOS
```
TESTE 1 - VERIFICAÇÃO DIMENSIONAL

Data: ___/___/_____  Técnico: _________________

Batimento radial:
- Máximo: _____ mm
- Mínimo: _____ mm  
- Total: _____ mm (Limite: 0.8mm)    □ OK  □ NOK

Batimento lateral:
- Máximo: _____ mm
- Mínimo: _____ mm
- Total: _____ mm (Limite: 0.5mm)    □ OK  □ NOK

Centragem:
- Lado esquerdo: _____ mm
- Lado direito: _____ mm
- Diferença: _____ mm (Limite: 2mm)   □ OK  □ NOK

Observações: _________________________________
```

### 2.3 TESTE 2: SISTEMA DE FREIO ESTÁTICO

#### PROCEDIMENTO
```
1. Conectar manômetro no sistema de freio
2. Acionar pedal de freio progressivamente:
   - Verificar resposta suave do pedal
   - Observar pressão no manômetro
   - Anotar pressão para travamento completo
   - LIMITE: 8-12 bar para travamento

3. Manter pressão máxima por 5 minutos:
   - Verificar vazamentos visuais
   - Anotar queda de pressão
   - LIMITE: < 0.5 bar queda

4. Teste de múltiplos acionamentos:
   - 20 acionamentos rápidos consecutivos
   - Verificar consistência da resposta
   - Observar temperatura do disco
```

#### REGISTRO DE RESULTADOS
```
TESTE 2 - SISTEMA DE FREIO ESTÁTICO

Data: ___/___/_____  Técnico: _________________

Pressão travamento: _____ bar (Limite: 8-12 bar)  □ OK  □ NOK
Queda pressão 5min: _____ bar (Limite: <0.5 bar)  □ OK  □ NOK
Vazamentos visuais: □ Ausentes  □ Presentes
Consistência pedal: □ Firme     □ Esponjoso
Temp. disco final:  _____ °C

Observações: _________________________________
```

### 2.4 TESTE 3: ALINHAMENTO DE CORRENTE

#### PROCEDIMENTO
```
1. Reinstalar corrente com tensão adequada:
   - Folga vertical: 25-35mm (meio do vão)
   - Tensão uniforme em toda volta

2. Verificar alinhamento usando gabarito:
   - Posicionar régua no pinhão dianteiro
   - Estender linha até cremalheira traseira
   - Medir desalinhamento lateral
   - LIMITE: ± 2mm

3. Verificar desgaste prematuro:
   - Inspeção visual dos dentes
   - Verificar lubrificação adequada
```

#### REGISTRO DE RESULTADOS
```
TESTE 3 - ALINHAMENTO CORRENTE

Data: ___/___/_____  Técnico: _________________

Folga corrente: _____ mm (Limite: 25-35mm)      □ OK  □ NOK
Alinhamento: _____ mm (Limite: ±2mm)            □ OK  □ NOK
Estado dos dentes: □ Bom  □ Desgaste leve  □ Ruim
Lubrificação: □ Adequada  □ Insuficiente

Observações: _________________________________
```

---

## 3. FASE 2 - TESTES DINÂMICOS CONTROLADOS

### 3.1 TESTE 4: ROTAÇÃO LIVRE

#### PROCEDIMENTO
```
1. Moto elevada, motor desligado
2. Girar roda traseira manualmente:
   - Verificar rotação suave sem travamentos
   - Observar ruídos anormais
   - Tempo de parada por inércia: > 15 segundos

3. Girar roda com motor ligado (marcha N):
   - Acelerar progressivamente até 3000 RPM
   - Observar vibrações anormais
   - Verificar temperatura dos rolamentos
   - LIMITE: < 60°C após 5 minutos
```

#### REGISTRO DE RESULTADOS
```
TESTE 4 - ROTAÇÃO LIVRE

Data: ___/___/_____  Técnico: _________________

Rotação manual:
- Suavidade: □ Excelente  □ Boa  □ Ruim
- Ruídos: □ Ausentes  □ Leves  □ Preocupantes
- Tempo parada: _____ seg (Limite: >15seg)     □ OK  □ NOK

Rotação com motor:
- Vibrações: □ Normais  □ Leves  □ Excessivas
- Temp. rolamentos: _____ °C (Limite: <60°C)   □ OK  □ NOK
- Ruídos: □ Normais  □ Anormais

Observações: _________________________________
```

### 3.2 TESTE 5: FRENAGEM DINÂMICA (ELEVADA)

#### PROCEDIMENTO
```
1. Motor ligado, roda girando livre (3000 RPM)
2. Aplicar freio progressivamente:
   - Verificar parada suave e controlada
   - Observar ausência de vibrações no freio
   - Medir tempo de parada
   - Verificar temperatura do disco

3. Teste de múltiplas frenagens:
   - 10 ciclos aceleração/frenagem
   - Verificar consistência
   - Observar superaquecimento
   - LIMITE: < 120°C no disco
```

#### REGISTRO DE RESULTADOS
```
TESTE 5 - FRENAGEM DINÂMICA

Data: ___/___/_____  Técnico: _________________

Frenagem inicial:
- Suavidade: □ Excelente  □ Boa  □ Brusca
- Vibrações: □ Ausentes  □ Leves  □ Fortes
- Tempo parada: _____ seg

Múltiplas frenagens:
- Consistência: □ Uniforme  □ Variável
- Temp. máxima: _____ °C (Limite: <120°C)      □ OK  □ NOK
- Sinais fadiga: □ Ausentes  □ Presentes

Observações: _________________________________
```

---

## 4. FASE 3 - TESTES FUNCIONAIS (BAIXA VELOCIDADE)

### 4.1 TESTE 6: PRIMEIRO TESTE DE RODAGEM

#### PREPARAÇÃO
```
LOCAL: Estacionamento vazio ou área fechada
VELOCIDADE: Máximo 20 km/h
DURAÇÃO: 30 minutos
PILOTO: Experiente e familiarizado com R3

EQUIPAMENTOS DE SEGURANÇA:
□ Capacete integral
□ Jaqueta com proteções
□ Luvas
□ Botas
□ Calça com proteções
□ Kit primeiros socorros disponível
```

#### PROCEDIMENTO
```
1. Inspeção pré-rodagem (10 minutos):
   - Verificar todos os torques
   - Inspeção visual completa
   - Teste de freio estático
   - Verificar pressão pneus

2. Primeira volta (5 km/h):
   - Atenção aos ruídos
   - Sensação de direção
   - Teste suave do freio traseiro

3. Velocidade progressiva (até 20 km/h):
   - Múltiplas curvas suaves
   - Testes de frenagem leve
   - Mudanças de marcha

4. Inspeção pós-teste:
   - Verificar aquecimento componentes
   - Inspeção visual desgastes
   - Verificar apertos
```

#### REGISTRO DE RESULTADOS
```
TESTE 6 - PRIMEIRO TESTE RODAGEM

Data: ___/___/_____  Piloto: _________________

Comportamento geral:
- Estabilidade: □ Excelente  □ Boa  □ Instável
- Direção: □ Neutra  □ Leve tendência  □ Puxando
- Freio traseiro: □ Eficiente  □ Adequado  □ Fraco

Ruídos anormais:
□ Ausentes  □ Leves  □ Preocupantes
Descrição: ___________________________________

Temperaturas pós-teste:
- Disco freio: _____ °C
- Rolamentos: _____ °C  
- Adaptadores: _____ °C

Inspeção visual:
□ Sem alterações  □ Desgaste leve  □ Problemas

Observações: _________________________________
```

### 4.2 TESTE 7: TESTE DE MANOBRABILIDADE

#### PROCEDIMENTO
```
1. Trajetória em "8" (5m diâmetro):
   - 10 voltas no sentido horário
   - 10 voltas no sentido anti-horário
   - Verificar diferenças comportamento

2. Frenagem em curva (velocidade baixa):
   - Curva suave + frenagem leve
   - Observar estabilidade
   - Sem travamento roda

3. Arranque e parada:
   - 10 ciclos parada/1ª marcha/parada
   - Verificar comportamento corrente
   - Observar desgaste cremalheira
```

#### REGISTRO DE RESULTADOS
```
TESTE 7 - MANOBRABILIDADE

Data: ___/___/_____  Piloto: _________________

Trajetória "8":
- Comportamento uniforme: □ Sim  □ Não
- Diferenças direcionais: □ Ausentes  □ Leves  □ Significativas

Frenagem em curva:
- Estabilidade: □ Mantida  □ Leve perda  □ Instável
- Travamento: □ Ausente  □ Presente

Arranques/paradas:
- Suavidade: □ Excelente  □ Boa  □ Brusca
- Corrente: □ Alinhada  □ Desalinhando  □ Problema

Observações: _________________________________
```

---

## 5. FASE 4 - TESTES DE PERFORMANCE

### 5.1 TESTE 8: TESTE DE VELOCIDADE PROGRESSIVA

#### PREPARAÇÃO
```
LOCAL: Pista fechada ou estrada vazia
CONDIÇÕES: Tempo seco, boa visibilidade
ACOMPANHAMENTO: Veículo de apoio com ferramentas
COMUNICAÇÃO: Rádio ou celular
```

#### PROCEDIMENTO
```
ETAPA 1: 40 km/h (10 km)
- Verificar estabilidade
- Testar frenagem em diferentes intensidades
- Observar comportamento corrente

ETAPA 2: 60 km/h (15 km)  
- Verificar vibrações alta velocidade
- Teste frenagem mais intensa
- Múltiplas mudanças marcha

ETAPA 3: 80 km/h (10 km)
- Estabilidade em reta
- Curvas progressivamente mais rápidas
- Frenagem de média intensidade

ETAPA 4: 100 km/h (5 km) - APENAS SE ETAPAS ANTERIORES OK
- Breve teste alta velocidade
- Frenagem controlada
- Retorno velocidades menores

PARADA OBRIGATÓRIA A CADA ETAPA PARA INSPEÇÃO
```

#### REGISTRO DE RESULTADOS
```
TESTE 8 - VELOCIDADE PROGRESSIVA

Data: ___/___/_____  Piloto: _________________

40 km/h (10 km):
- Estabilidade: □ Excelente  □ Boa  □ Problemas
- Frenagem: □ Eficiente  □ Adequada  □ Insuficiente
- Corrente: □ Alinhada  □ OK  □ Problemas

60 km/h (15 km):
- Vibrações: □ Ausentes  □ Leves  □ Perceptíveis
- Performance: □ Normal  □ Levemente diferente  □ Problema

80 km/h (10 km):
- Estabilidade reta: □ Excelente  □ Boa  □ Instável
- Curvas: □ Normais  □ Diferentes  □ Problemáticas

100 km/h (5 km): □ Realizado  □ Não realizado
- Motivo não realização: _________________________

Temperaturas finais:
- Disco: _____ °C    - Rolamentos: _____ °C
- Adaptadores: _____ °C

Observações: _________________________________
```

### 5.2 TESTE 9: TESTE DE FRENAGEM DE EMERGÊNCIA

#### PROCEDIMENTO (ATENÇÃO: TESTE DE ALTO RISCO)
```
PREPARAÇÃO ESPECIAL:
□ Piloto muito experiente
□ Pista com run-off área
□ Equipamentos segurança completos
□ Equipe médica standby
□ Múltiplos observadores

PROTOCOLO:
1. Velocidade 60 km/h em linha reta
2. Frenagem máxima (combinada diant./tras.)
3. Medir distância parada
4. Verificar estabilidade durante frenagem
5. REPETIR APENAS 3 VEZES (risco superaquecimento)

CRITÉRIOS SEGURANÇA:
- Qualquer instabilidade = PARAR TESTE
- Temperatura disco > 180°C = PARAR
- Fadiga freio = PARAR IMEDIATAMENTE
```

#### REGISTRO DE RESULTADOS
```
TESTE 9 - FRENAGEM EMERGÊNCIA

Data: ___/___/_____  Piloto: _________________

Teste 1 (60 km/h):
- Distância parada: _____ m
- Estabilidade: □ Mantida  □ Leve perda  □ Instável
- Temp. disco: _____ °C

Teste 2 (60 km/h):
- Distância parada: _____ m  
- Estabilidade: □ Mantida  □ Leve perda  □ Instável
- Temp. disco: _____ °C

Teste 3 (60 km/h):
- Distância parada: _____ m
- Estabilidade: □ Mantida  □ Leve perda  □ Instável
- Temp. disco: _____ °C

COMPARAÇÃO COM R3 ORIGINAL:
- Performance: □ Igual  □ Melhor  □ Pior
- Diferença estimada: _____ %

Observações: _________________________________
```

---

## 6. FASE 5 - TESTES DE DURABILIDADE

### 6.1 TESTE 10: RODAGEM ESTENDIDA

#### PROTOCOLO (500 KM INICIAIS)
```
CRONOGRAMA:
- Primeira semana: 50 km/dia (velocidade < 80 km/h)
- Segunda semana: 75 km/dia (velocidade < 100 km/h)
- Terceira semana: Uso normal limitado

INSPEÇÕES OBRIGATÓRIAS:
□ A cada 50 km: Inspeção visual + apertos
□ A cada 150 km: Medições dimensionais
□ A cada 300 km: Inspeção completa sistema

REGISTRO DIÁRIO:
- Quilometragem
- Condições uso
- Temperaturas
- Observações comportamento
```

#### PONTOS DE VERIFICAÇÃO CRÍTICOS
```
INSPEÇÃO 150 KM:
□ Batimento roda (limite inalterado)
□ Folga buchas adaptadoras
□ Desgaste rolamentos
□ Alinhamento corrente
□ Aperto parafusos (re-torque se necessário)
□ Desgaste pastilhas freio

INSPEÇÃO 300 KM:
□ Verificação dimensional completa
□ Análise desgaste componentes
□ Teste performance (repetir testes 6-8)
□ Avaliação térmica
□ Documentação fotográfica

INSPEÇÃO 500 KM:
□ Avaliação final durabilidade
□ Comparação com dados iniciais
□ Decisão continuidade projeto
□ Relatório técnico final
```

---

## 7. CRITÉRIOS DE APROVAÇÃO/REPROVAÇÃO

### 7.1 CRITÉRIOS DE APROVAÇÃO

```
APROVAÇÃO FASE 1 (Estáticos):
□ Batimento total < 0.8mm
□ Sistema freio sem vazamentos
□ Alinhamento corrente ± 2mm
□ Todas temperaturas dentro limites

APROVAÇÃO FASE 2 (Dinâmicos):
□ Rotação suave sem ruídos
□ Frenagem consistente
□ Temperaturas < limites especificados
□ Ausência vibrações anormais

APROVAÇÃO FASE 3 (Funcionais):
□ Comportamento direcional normal
□ Frenagem eficiente e controlada
□ Manobrabilidade adequada
□ Sem desgastes prematuros

APROVAÇÃO FASE 4 (Performance):
□ Estabilidade em todas velocidades
□ Performance frenagem ≥ 95% original
□ Ausência problemas térmicos
□ Comportamento previsível

APROVAÇÃO FASE 5 (Durabilidade):
□ Sem desgastes excessivos após 500km
□ Manutenção características iniciais
□ Ausência falhas componentes
□ Viabilidade uso contínuo
```

### 7.2 CRITÉRIOS DE REPROVAÇÃO (PARADA IMEDIATA)

```
⛔ REPROVAÇÃO AUTOMÁTICA:
- Qualquer fratura componente
- Vazamento fluido freio
- Desalinhamento >5mm corrente
- Temperatura >200°C disco
- Batimento >1.5mm roda
- Instabilidade direcional
- Perda eficiência freio >20%
- Desgaste prematuro crítico
- Ruídos indicativos falha
- Folga excessiva eixo

AÇÃO: Parada imediata + análise falha + correção
```

---

## 8. DOCUMENTAÇÃO E RELATÓRIOS

### 8.1 RELATÓRIO FINAL

#### ESTRUTURA DO RELATÓRIO
```
1. RESUMO EXECUTIVO
2. METODOLOGIA TESTE
3. RESULTADOS POR FASE
4. ANÁLISE COMPARATIVA (R3 original vs modificada)
5. CONCLUSÕES SEGURANÇA
6. RECOMENDAÇÕES USO
7. CRONOGRAMA MANUTENÇÃO
8. ANEXOS (fotos, gráficos, medições)
```

### 8.2 CERTIFICAÇÃO

#### DOCUMENTOS NECESSÁRIOS
```
□ Relatório completo testes
□ Cálculos engenharia validados
□ Fotos antes/durante/depois
□ Medições dimensionais completas
□ Aprovação engenheiro responsável
□ Termo responsabilidade piloto
□ Recomendações uso seguro
□ Cronograma inspeções
```

---

**IMPORTANTE:** Este protocolo de testes deve ser executado integralmente antes da liberação do sistema para uso normal. A segurança é prioridade absoluta e qualquer desvio dos parâmetros estabelecidos deve resultar em reavaliação completa do projeto.

---

**Autor:** Projeto de Adaptação MT-07/R3
**Data:** Janeiro 2025
**Versão:** 1.6
**Aprovação Técnica:** [Aguardando]
**Aprovação Segurança:** [Aguardando]