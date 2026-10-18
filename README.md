Gêmeo Digital Térmico de Hardware Computacional

Disciplina: Fundamentos de Engenharia  
Sistema-Alvo: Placa GPU de inferência de IA em operação contínua (TDP = 120 W)

1. Apresentação do Projeto
Este repositório contém os artefatos do projeto prático de Gêmeo Digital Térmico. O objetivo é projetar, simular e justificar a solução de dissipação térmica para uma GPU de inteligência artificial operando sob carga intensa, garantindo a integridade térmica do chip com menor impacto ambiental e custo otimizado.

2. Membros da Equipe: Gabriela dos Santos Dias - 22653275

3. Tabela de Resultados Técnicos

| Eixo Temático | Parâmetro / Ferramenta | Resultado / Decisão de Projeto |
| Ciência dos Materiais | Alumínio 6063-T6 & Cobre | Alta condutividade térmica (200 a 398 W/m·K) e estrutura cristalina CFC. |
| Química | Interface Térmica & Oxidação | Aplicação de TIM e camada passiva de Al2O3 protetora contra corrosão. |
Expressão Gráfica (CAD) | FreeCAD / Desenho Técnico | Modelagem 3D do dissipador de aletas e desenho cotado segundo normas ABNT. |
Fenômenos de Transporte | Google Colab (Python / Diferenças Finitas) | Temperatura máxima calculada no chip: 68,5 °C (Abaixo do limite de 85 °C). |
| Mecânica dos Sólidos | Tensão Térmica e Dilatação | Tensão estimada (~61,2 MPa) segura frente ao escoamento do material. |
| Sustentabilidade | Ciclo de Vida e PUE | Uso de alumínio reciclado (>95% de reciclabilidade) e otimização do arrefecimento. |

4. Vídeo Demonstrativo


5. Estrutura do Repositório
/cad — Ficheiro tridimensional do FreeCAD e desenho técnico cotado.
/simulacao — Notbook em Python (.ipynb) executável via Google Colab.
/relatorio — Relatório técnico completo em formato PDF (Normas ABNT).
/media — Gráficos de perfil térmico e imagens visuais.
