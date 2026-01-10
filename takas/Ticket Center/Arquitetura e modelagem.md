### Tudo que pode ser vinculado ao Ticket

	1. ID: number
	2. Title: string
	3. Criticality
		1. id
		2. description
			1. low
			2. medium
			3. high
			4. critical	
	4. Priority: boolean
	5. Actual Status: Status
	6. Previous Status: Status
	7. Ticket Type
		1. id
		2. description
			1. Bug
			2. User assist
			3. Improvement
			4. New development
	8. Software
		1. id
		2. name
		3. description
		4. module id
		5. active
		6. created
		7. updated
	9. Module
		1. id
		2. name
		3. description
		4. active
		5. created
		6. updated
	10. Team
		1. id
		2. name
		3. description
		4. user id
		5. active
		6. created
		7. updated
	11. Product Type
		1. id
		2. name
		3. description
		4. software id
		5. active
		6. created
		7. updated
	12. Origin // deixar essa atribuição para N1
		1. id
		2. name
		3. description
		4. active
		5. created
		6. updated
	13. Requester: User
	14. Assignee: User
	15. Due date: timestamp
	16. Expire date: timestamp
	17. Created: timestamp
	18. Updated: timestamp
	19. Concluded: timestamp
	20. Attachments
		1. id
		2. originalName
		3. url
		4. size
		5. type
	21. History
		1. id
		2. action
		3. fieldChange
		4. previousValue
		5. newValue
		6. user
		7. created
	22. Requester Rating
	23. Assignee Rating
	24. Difficulty
		1. id
		2. description
			1. P
			2. M
			3. G
			4. GG
		3. value
	25. Forms: json

### User
	1. ID
	2. Name
	3. Email
	4. Division
	5. Unity

### Status
	1. id
	2. description
		1. backlog
		2. analise n1
		3. analise n2
		4. em desenvolvimento
		5. em testes
		6. em revisão
		7. aguardando deploy
		8. aguardando retorno do solicitante
		9. concluido
		10. cancelado


