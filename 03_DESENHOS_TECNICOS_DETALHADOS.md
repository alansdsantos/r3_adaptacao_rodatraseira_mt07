# DESENHOS TÉCNICOS DETALHADOS
## Adaptação Roda Traseira MT-07 em Yamaha R3 2021

---

## 1. VISTA EXPLODIDA DO CONJUNTO (Vista Lateral)

```
BALANÇA R3                    COMPONENTES MT-07              ADAPTADORES

    ╔═══╗                           ╔═══════════════╗             ╔═╗
    ║   ║                           ║    CUBO       ║             ║B║
    ║   ║ ←── DROPOUT L.             ║    MT-07      ║             ║U║
    ║   ║                           ║               ║             ║C║
    ║   ║     [EIXO R3 Ø15mm]       ╠═══════════════╣             ║H║
════╬═══╬════════════════════════════╬═══════════════╬═════════════╬═╬═══
    ║   ║                           ║               ║             ║A║
    ║   ║                           ║    RODA       ║             ║ ║
    ║   ║ ←── DROPOUT R.             ║    MT-07      ║             ║ ║
    ║   ║                           ║               ║             ║ ║
    ╚═══╝                           ╚═══════════════╝             ╚═╝

    |<-- 145mm -->|                 |<--- 95mm --->|              |15|
                                                                   |mm|
```

---

## 2. BUCHA ADAPTADORA - DESENHO TÉCNICO

### 2.1 VISTA FRONTAL E CORTE
```
        ╔═══════════════════════════════════╗  ← Ø16.98mm (H7)
        ║                                   ║
        ║         BUCHA BRONZE              ║
        ║                                   ║
        ║    ╔═══════════════════════╗      ║  ← Ø15.02mm (g6)
        ║    ║                       ║      ║
        ║    ║       EIXO R3         ║      ║
        ║    ║       Ø15mm           ║      ║
        ║    ║                       ║      ║
        ║    ╚═══════════════════════╝      ║
        ║                                   ║
        ╚═══════════════════════════════════╝
        |<------------- 30mm -------------->|

ESPECIFICAÇÕES:
- Material: Bronze Fosforoso CuSn8
- Tolerância externa: H7 (+0.018/0)
- Tolerância interna: g6 (-0.009/-0.020)
- Acabamento superficial: Ra 1.6 μm
- Chanfro entrada: 0.5 x 45°
```

### 2.2 COTAS DETALHADAS
```
     0.5 x 45°
         ╲
          ╲   ╔═══════════════════════════╗
           ╲  ║                           ║ ← 16.98 +0.018
            ╲ ║                           ║      -0.000
             ╲║                           ║
          ────╬═══════════════════════════╬──── ← Centro
             ╱║                           ║
            ╱ ║                           ║ ← 15.02 +0.000
           ╱  ║                           ║      -0.020
          ╱   ╚═══════════════════════════╝
         ╱
     0.5 x 45°
         |<---------- 30.0 ±0.1 ---------->|
```

---

## 3. ADAPTADOR DE PINÇA - DESENHO TÉCNICO

### 3.1 VISTA SUPERIOR
```
                   ADAPTADOR PINÇA DE FREIO
    
    ╔═══════════════════════════════════════════════════════════╗
    ║   ○                                               ○       ║ ← 15mm espessura
    ║     ← M10x1.5 (Fixação pinça)      M8x1.25 →       ║
    ║                                                           ║
    ║           ╔═══════════════════════════════╗               ║
    ║           ║                               ║               ║
    ║           ║    RECORTE PARA DISCO         ║               ║
    ║           ║    Ø260mm (folga 15mm)       ║               ║
    ║           ║                               ║               ║
    ║           ╚═══════════════════════════════╝               ║
    ║                                                           ║
    ║                                               ○       ○   ║
    ║                                        M8x1.25 →         ║
    ╚═══════════════════════════════════════════════════════════╝
    |<-------------------- 120mm -------------------->|
```

### 3.2 VISTA LATERAL COM COTAS
```
         12.5mm ← OFFSET RADIAL
           │
           ▼
    ╔══════════════════╗
    ║                  ║ ← PINÇA R3 (posição original)
    ║      PINÇA       ║
    ║                  ║
    ╚══════════════════╝
           │
           │ ← ADAPTADOR
    ╔══════════════════╗
    ║                  ║ ← 15mm espessura
    ╚══════════════════╝
           │
    ╔══════════════════╗
    ║    BALANÇA R3    ║
    ╚══════════════════╝

CÁLCULO OFFSET:
Raio disco MT-07: 122.5mm
Raio disco R3: 110mm
Diferença: 12.5mm → OFFSET NECESSÁRIO
```

---

## 4. ALINHAMENTO DE CORRENTE - DIAGRAMA

### 4.1 VISTA SUPERIOR
```
                    ALINHAMENTO CORRENTE

    PINHÃO DIANTEIRO                  CREMALHEIRA TRASEIRA
          │                                    │
          ▼                                    ▼
    ╔═══════════╗                        ╔═════════╗
    ║     R3    ║◄────── CORRENTE ──────►║  MT-07  ║
    ║   14T     ║        (520)           ║   43T   ║
    ╚═══════════╝                        ╚═════════╝
          │                                    │
          │                                    │
       Original                           +20mm OFFSET →
       Position                          (para direita)

    |<-------------- 1380mm WHEELBASE -------------->|
                        (R3 Original)
```

### 4.2 OFFSET DA CREMALHEIRA
```
                 VISTA TRASEIRA

    BALANÇA R3              RODA MT-07               NOVO POSICIONAMENTO
        │                       │                         │
        ▼                       ▼                         ▼
    ╔═══════╗              ╔══════════╗               ╔══════════╗
    ║       ║              ║          ║               ║    ○     ║ ← Cremalheira
    ║   ○   ║ ← Original   ║    140mm ║               ║  offset  ║   (+20mm)
    ║Position              ║          ║               ║  180mm   ║
    ╚═══════╝              ╚══════════╝               ╚══════════╝
        │                       │                         │
        │                       │                         │
    Centro Line            Pneu Original              Pneu MT-07
    Original R3            R3 (140mm)                 (180mm)

    ESPAÇADOR NECESSÁRIO: 20mm
```

---

## 5. SEQUÊNCIA DE MONTAGEM - DIAGRAMA

### 5.1 PASSO 1: PREPARAÇÃO DO CUBO
```
CUBO MT-07 ORIGINAL          CUBO COM BUCHAS INSTALADAS

╔═══════════════════╗        ╔═══════════════════╗
║                   ║   →    ║ [B] ┌─────┐ [B]   ║
║    Ø17mm         ║        ║  U  │EIXO │  U    ║
║                   ║        ║  C  │15mm │  C    ║
║    (Vazio)        ║        ║  H  │     │  H    ║
║                   ║        ║  A  └─────┘  A    ║
╚═══════════════════╝        ╚═══════════════════╝

B = Bucha Adaptadora (Bronze)
U = Usinagem de precisão necessária
C = Centragem crítica
H = Ajuste H7/g6
A = Acabamento Ra 1.6
```

### 5.2 PASSO 2: INSTALAÇÃO DO SISTEMA DE FREIO
```
PINÇA ORIGINAL R3            PINÇA COM ADAPTADOR

    ╔══════╗                     ╔══════╗
    ║ PINÇA║ ← 220mm              ║ PINÇA║ ← 245mm
    ║  R3  ║   Disco              ║  R3  ║   Disco
    ║      ║                     ║      ║
    ╚══════╝                     ╚══════╝
        │                            │
        │                            │ ← +12.5mm
    ╔══════╗                     ╔══════╗
    ║BALANÇA               ║ADAPT.║
    ║  R3  ║                     ║ 15mm ║
    ╚══════╝                     ╚══════╝
                                     │
                                 ╔══════╗
                                 ║BALANÇA
                                 ║  R3  ║
                                 ╚══════╝
```

---

## 6. VERIFICAÇÕES DIMENSIONAIS

### 6.1 LISTA DE VERIFICAÇÃO PRÉ-MONTAGEM
```
□ Batimento radial cubo: < 0.05mm
□ Batimento lateral cubo: < 0.03mm
□ Ajuste buchas: Sem folgas
□ Centragem disco: ±0.1mm
□ Paralelismo adaptador: ±0.05mm
□ Torque parafusos: Conforme especificação
□ Folga corrente: 25-35mm
□ Alinhamento corrente: ±2mm lateral
```

### 6.2 FERRAMENTAS DE VERIFICAÇÃO
```
- Relógio comparador (0.01mm)
- Esquadro de precisão
- Gabarito de alinhamento
- Torquímetro calibrado
- Paquímetro digital
- Micrômetro
```

---

## 7. TOLERÂNCIAS CRÍTICAS

### 7.1 RESUMO DAS TOLERÂNCIAS PRINCIPAIS
```
COMPONENTE                  TOLERÂNCIA        VERIFICAÇÃO
─────────────────────────────────────────────────────────
Bucha externa              H7 (+0.018/0)      Micrômetro
Bucha interna              g6 (-0.009/-0.020) Paquímetro
Adaptador pinça            ±0.1mm             Esquadro
Centragem roda             ±0.5mm radial      Relógio
Alinhamento corrente       ±2mm lateral       Gabarito
Torque parafusos          ±5% especificado    Torquímetro
```

---

## 8. MATERIAIS E TRATAMENTOS

### 8.1 ESPECIFICAÇÕES DOS MATERIAIS
```
BUCHA ADAPTADORA:
- Material: Bronze fosforoso CuSn8
- Dureza: 85-95 HB
- Resistência tração: 250 MPa
- Tratamento: Recozimento

ADAPTADOR PINÇA:
- Material: Aço 1020 ou Alumínio 7075-T6
- Tratamento: Fosfatização ou Anodização
- Proteção: Primer + tinta automotiva

PARAFUSOS:
- Classe: 8.8 (aço) ou A4-80 (inox)
- Tratamento: Zincagem branca
- Vedação: Loctite 243 (médio)
```

---

**NOTA IMPORTANTE:** Todos os desenhos devem ser verificados fisicamente antes da fabricação. As dimensões aqui apresentadas são baseadas em especificações padrão e podem necessitar ajustes conforme as medições reais dos componentes.

---

**Autor:** Projeto de Adaptação MT-07/R3
**Data:** Janeiro 2025
**Versão:** 1.2