Data som har använts i detta projekt är foljande:
    1. Tomtyta
    2. Bebyggelsetyp
    3. Tryck
    4. Antal DN20 mätare i varje fastighet
    6. Antal DN25 mätare i varje fastighet
    7. Fastighetens årsförbrukning för förra året
    8. Veckodag
    9. Postort
    10. Mätdata från vattenmätare i medelförbrukning per veckodag

Modellen tränades endast på data från villor. 1-9 ovan användes som input till ANN-modellen för att träna den 
att hitta medelförbrukningen under en viss dag (10 ovan) för en fastighet.