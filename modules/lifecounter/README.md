# lifecounter

[![Platform](https://img.shields.io/badge/platform-MagicMirror2-informational)](https://github.com/razvanh255/MagicMirror2)
[![CC-0 license](https://img.shields.io/badge/License-CC--4.0-blue.svg)](https://creativecommons.org/licenses/by-nd/4.0)


As a number, 1 billion is an almost unimaginable. Here’s a way to help you imagine it. Use 1 billion—with its nine zeros—to measure your time. Look forward or back to your 1-billionth-second birthday (aprox. 31 years, 8 months, 9 days) or 2-billionth-second birthday (aprox. 63 years, 4 months, 18 days) maybe even 3-billionth-second birthday (aprox. 95 years, 27 days). Mark it. Celebrate it. Then keep counting. Measure 1 billion with the seconds of your life.

<br>(1967-10-13)

	{
		module: "lifecounter",
		position: "top_left",
		config: {
			birthday: "1970-01-01 00:00:00",	// year, month, day, 24 hour birthday time
			counter: "seconds",			// seconds, minutes, hours, months, weeks, days, years
			before: "UNIX Epoch Time",		// your comment before
			after: "seconds",			// your comment after
			cssclass: "ssmall",
			decimalSymbol: config.decimal,
		}
	},

Designed by Răzvan Cristea https://github.com/razvanh255 Creative Commons BY-NC-SA 4.0, Romania.
