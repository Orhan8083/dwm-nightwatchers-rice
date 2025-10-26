# dwm-nightwatchers-rice

	{ ram_perc,  "   %s " ,              NULL },
	{ cpu_perc,  "|   %s " ,             NULL },
	{ wifi_perc, "| 󰖩  %s " ,          "wlan0" },
	{ run_command,  "| 󰕾 %4s ", "amixer sget Master | awk -F\"[][]\" '/%/ { print $2 }' | head -n1"},
	{ datetime, "|  %s " ,         "%F | 󰥔 %T" },
