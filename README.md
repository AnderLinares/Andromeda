## Adromeda

    [{
	"$project" : { "Type" : "Local Project",
		"Name" : "Andromeda",
		"Description" : "Sistema de comidas, con perfiles de usuario, mas comentario por comidas, támbien galleria de comidas, más correo de soporte",
		"From" : { "$django" : { "Version" : "1.5.1"},},
		"Group" : { "G" : "Public", "B" : "Private", "H" : "Deploy"},
		"_id" : 1
	},
    }]

