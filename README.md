# attack-eval-scoring-by-Endgame
@ianmcshane | ian@endgame.com

This repo is forked from Josh Zelonis' work around his initial blog post on 
the MITRE ATT&CK evaluation.

To understand the context of these scripts, please see
https://www.endgame.com/blog/technical-blog/heres-how-we-do-numbers

## delayed.py
This script counts each occurance of a delayed detection, for all vendor data in /data.
There is no weighting for different types of detection with the delayed modifier.

## no_context.py
This script counts each occurance of an enrichement or telemetry detection only, no modifiers, for all vendor data in /data.

## no_delay.py
This script counts each occurance of an enrichement or telemetry detection only, no modifiers, for all vendor data in /data.

## real_time.py
This script displays Forresters count of "Real Time Alerts" for all vendor data in /data..

## what_matters.py
This script implements weightings according to how Endgame perceives importance.  Please see https://www.endgame.com/blog/technical-blog/heres-how-we-do-numbers for more information