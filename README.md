{
  "request": [
    {
      "Sudo_Command": "viinttab",
      "Description": "edit inittab file",
      "User": "*",
      "Group": "tsgsecur",
      "Prompt_for_password": "n",
      "Day_of_week": 123456.0,
      "Start_time": 0.0,
      "End_time": 1.0,
      "Effective_User": "root",
      "Effective_group": "*",
      "pass_arguments": "y",
      "full_path_of_command": "/bin/vi/etc/inittab"
    },
    {
      "Sudo_Command": "telinit",
      "Description": "refresh init",
      "User": "*",
      "Group": "tsgsecur",
      "Prompt_for_password": "n",
      "Day_of_week": 123456.0,
      "Start_time": 0.0,
      "End_time": 1.0,
      "Effective_User": "root",
      "Effective_group": "*",
      "pass_arguments": "y",
      "full_path_of_command": "/sbin/init q"
    },
    {
      "Sudo_Command": "viguardini_8",
      "Description": "edit ver 8 agent .ini file",
      "User": "*",
      "Group": "tsgsecur",
      "Prompt_for_password": "n",
      "Day_of_week": 123456.0,
      "Start_time": 0.0,
      "End_time": 1.0,
      "Effective_User": "root",
      "Effective_group": "*",
      "pass_arguments": "y",
      "full_path_of_command": "/bin/vi/fisc/guardium/modules/STAP/current/guard"
    }
  ]
}
