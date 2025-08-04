### 1. **Usuário**
- **Atributos**: `Nome`, `Email`, `Senha`
- Entidade central do sistema.
- Relaciona-se com diversas outras entidades como horários de estudo, metas, notificações e sincronizações.

### 2. **HorárioEstudo**
- **Atributos**: `diaSemana`, `horaInicio`, `horaFinal`, `materia`
- Cada usuário pode ter **vários horários de estudo**.
- Cada horário pertence a **um único usuário**.

### 3. **Relatório**
- **Atributos**: `periodoInicio`, `periodoFim`, `desempenho`
- Cada usuário possui **um único relatório** associado.

### 4. **Meta**
- **Atributos**: `descricao`, `prazo`
- Representa uma meta individual do usuário com um prazo definido.

### 5. **Notificação**
- **Atributos**: `mensagem`, `horarioEnvio`, `tipo`
- Cada usuário pode ter uma **notificação configurada**.

### 6. **Sincronização**
- **Atributos**: `servico`, `status`
- Relaciona-se com o usuário e um **calendário externo**.
- Representa a **integração ativa** com um serviço externo.

### 7. **CalendárioExterno**
- **Atributos**: `nomeServico`, `tokenAcesso`
- Associado a uma sincronização.
