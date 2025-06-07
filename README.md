@Override 
public void onClick(View v) 
{ 
    if (v == casa) 
    { 
        //Crea un nuevo objeto que se utiliza para iniciar otra actividad 
dentro de la aplicación. 
        Intent transicion = new Intent(pantalla_principal.this, 
MainActivity.class); 
 
        //Hace que la actividad  se inicie y se muestre en la pantalla. 
        startActivity(transicion); // Start activity for result 
    } 
 
    if (v == pp) 
    { 
        Intent transicion = new Intent(pantalla_principal.this, 
primer_piso.class); 
        startActivity(transicion); // Start activity for result 
    } 
 
    if (v == sp) 
    { 
        Intent transicion = new Intent(pantalla_principal.this, 
segundo_piso.class); 
        startActivity(transicion); // Start activity for result 
    } 
 
    if (v == tp) 
    { 
        Intent transicion = new Intent(pantalla_principal.this, 
tercer_piso.class); 
        startActivity(transicion); // Start activity for result 
    } 
 
    if (v == eg) 
    { 
        Intent transicion = new Intent(pantalla_principal.this, 
exterior_garaje.class); 
        startActivity(transicion); // Start activity for result 
    } 
} 
