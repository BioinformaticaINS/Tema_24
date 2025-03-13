# Tema 24: Bases de datos de proteínas, Métodos de determinación de estructuras de proteínas, Estructura de proteínas y Modelamiento por homología

---

### **Objetivo de la sesión:**
Al finalizar la sesión, los estudiantes serán capaces de utilizar bases de datos de proteínas, comprender los métodos de determinación de estructuras protéicas, analizar los niveles de organización estructural de las proteínas y aplicar técnicas de modelamiento por homología para predecir estructuras proteicas.

---

### **Agenda:**

1. **Introducción a las bases de datos de proteínas** (30 minutos)
2. **Métodos de determinación de estructuras de proteínas** (30 minutos)
3. **Estructura de proteínas** (30 minutos)
4. **Modelamiento por homología** (1 hora)
5. **Actividad práctica y discusión** (30 minutos)

---

### **1. Introducción a las bases de datos de proteínas** (30 minutos)

**Contenido:**
- **¿Qué es una proteína?**
  - Definición básica: Las proteínas son moléculas formadas por cadenas de aminoácidos.
  - Importancia en los organismos vivos: Desempeñan un papel fundamental en la formación y reparación de tejidos, desarrollo corporal e intelectual.
  - Ejemplos de proteínas: Actina y Miosina (Músculo), Celulosa (Árbol), Bacterias y Virus (Pirazinamida y Spike).

- **¿Porqué es importante conocer la estructura de la proteína?**
  - Función de las proteínas: Multitud de funcionabilidades.
  - Relación estructura-función: Existe una relación muy directa.
      * Filamentosas: Colágeno o la actina
      * Grapa: Espectrinas y filaminas
      * Anulares: DNA polimerasa
      * Conducto: Porina

- **Tamaño de las proteínas**
  - Célula --> (1x10-6 m) µ micras
  - Ribosoma --> (1x10-9 m) nanómetros
  - Proteína --> (1x10-10 m) angstroms

![](https://www.aula2005.com/html/cn3eso/04moleculescelules/mides300es.jpg)


- **Bases de datos de proteínas:**
  - **UniProt:** Base de datos de secuencias de proteínas y información funcional.
  - **Protein Data Bank (PDB):** Repositorio mundial de estructuras 3D de proteínas y otras macromoléculas.
  - **ExPASy:** Portal bioinformático que ofrece acceso a bases de datos y herramientas para la investigación en ciencias de la vida.

**Actividad:**
- Exploración de UniProt y PDB para buscar una proteína específica (e.g., "alkaline serine protease").
- Discusión sobre la información obtenida (secuencia, estructura, función, etc.).

---

### **2. Métodos de determinación de estructuras de proteínas** (30 minutos)

**Contenido:**
- **Cristalografía de rayos X:**
  - Utiliza rayos X para determinar la estructura de proteínas cristalizadas.
  - Proporciona una resolución atómica.
  
- **Resonancia Magnética Nuclear (RMN):**
  - Basada en las propiedades mecánicas cuánticas de los átomos.
  - Útil para proteínas en solución.

- **Criomicroscopía electrónica (Cryo-EM):**
  - Permite visualizar proteínas en su estado nativo.
  - Ideal para grandes complejos proteicos.

**Actividad:**
- Discusión sobre las ventajas y limitaciones de cada método.
- Visualización de estructuras determinadas por diferentes métodos en PDB.

---

### **3. Estructura de proteínas** (30 minutos)

**Contenido:**
- **Niveles de organización estructural:**
  - **Estructura primaria:** Secuencia de aminoácidos.
  - **Estructura secundaria:** Formación de hélices alfa y láminas beta.
  - **Estructura terciaria:** Plegamiento completo de la cadena polipeptídica.
  - **Estructura cuaternaria:** Asociación de múltiples cadenas polipeptídicas.

- **Relación estructura-función:**
  - La estructura de una proteína determina su función.
  - Ejemplos: Colágeno (filamentosa), DNA polimerasa (anular), Porina (conducto).

**Actividad:**
- Análisis de la estructura primaria de una proteína usando ProtParam.
- Visualización de estructuras secundarias y terciarias en PyMOL.

---

### **4. Modelamiento por homología** (1 hora)

**Contenido:**
- **¿Qué es el modelamiento por homología?**
  - Predicción de la estructura 3D de una proteína basada en la comparación con estructuras conocidas.
  - Se basa en la similitud de secuencias y estructuras.

- **Pasos del modelamiento por homología:**
  1. Selección de plantilla.
  2. Alineamiento de secuencias.
  3. Creación del esqueleto del modelo.
  4. Modelado de bucles.
  5. Perfeccionamiento de la cadena lateral.
  6. Refinamiento mediante funciones de energía.

- **Herramientas de modelamiento:**
  - **HHpred:** Herramienta para la predicción de homología.
  - **Modeller:** Software para el modelado de estructuras proteicas.
  - **AlphaFold2:** Modelado basado en aprendizaje automático.

**Actividad:**
- Modelado de una proteína misteriosa usando HHpred y Modeller.
- Evaluación del modelo generado usando Verify3D.

---

### **Referencias:**
- Pazos, F., & Chagoyen, M. (2015). *Practical Protein Bioinformatics*. Springer.
- Documentación de UniProt, PDB, HHpred, Modeller, y AlphaFold2.
