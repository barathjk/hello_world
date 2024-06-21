all_dict = {"SWP-69304": {
        "Bat": {"Concept": 3, "Design": 0, "Ready": 0, "Obsolete": 0, "Deleted": 0},
        "Intake": {"Concept": 0, "Design": 0, "Ready": 7, "Obsolete": 0, "Deleted": 0},
        "Intake_ext": {
            "Concept": 0,
            "Design": 0,
            "Ready": 2,
            "Obsolete": 1,
            "Deleted": 0,
        },
        "Full": {"Concept": 0, "Design": 0, "Ready": 0, "Obsolete": 0, "Deleted": 0},
        "Zedis": {"Concept": 0, "Design": 0, "Ready": 0, "Obsolete": 0, "Deleted": 0},
    },
"SWP-100109#SWP-108165": {
	"Bat": {"Concept": 2, "Design": 0, "Ready": 0, "Obsolete": 0, "Deleted": 0},
	"Intake": {"Concept": 0, "Design": 0, "Ready": 1, "Obsolete": 0, "Deleted": 0},
	"Intake_ext": {
		"Concept": 0,
		"Design": 0,
		"Ready": 0,
		"Obsolete": 0,
		"Deleted": 0,
	},
	"Full": {"Concept": 0, "Design": 0, "Ready": 0, "Obsolete": 0, "Deleted": 0},
        "Zedis": {"Concept": 0, "Design": 0, "Ready": 0, "Obsolete": 0, "Deleted": 0},
	},
	}
	
The final result should be like this, to add the values of all dict of dict values
	final_dict = {"SWP-100109#SWP-108165#SWP-69304": {
	"Bat": {"Concept": 5, "Design": 0, "Ready": 0, "Obsolete": 0, "Deleted": 0},
	"Intake": {"Concept": 0, "Design": 0, "Ready": 8, "Obsolete": 0, "Deleted": 0},
	"Intake_ext": {
		"Concept": 0,
		"Design": 0,
		"Ready": 2,
		"Obsolete": 1,
		"Deleted": 0,
	},
	"Full": {"Concept": 0, "Design": 0, "Ready": 0, "Obsolete": 0, "Deleted": 0},
        "Zedis": {"Concept": 0, "Design": 0, "Ready": 0, "Obsolete": 0, "Deleted": 0},
	},}
