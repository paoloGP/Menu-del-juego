# Menu-del-juego
void menu_del_juego(){
    int a;
    tipo arr[9][9] = {};
    cout << "MENU - Juego Senku" << "\n" << "*******************" << endl;
    cout << "(1) ingles" << endl << "(2) frances" << endl << "(3) aleman" << endl;
    cout << "*******************" << endl;
    do {
        cout << "Elegir modo:";
        cin >> a;
    }while (a < 1 && a > 3);
    arr[9][9] = tablero(arr,a);
    imprimir(arr);

}
