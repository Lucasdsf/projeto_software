#include <iostream>
using namespace std;

void maximoMinimo(int *v, int N, int *maximo, int *minimo) {
  *maximo = v[0];
  *minimo = v[0];
  for (int i = 0; i < N; i++) {
    if (v[i] < *minimo) *minimo = v[i];
    if (v[i] > *maximo) *maximo = v[i];
  }
}



int main() {
  int N,*v,maximo,minimo,aux;
  cout << "Insira a quantidade de valores do vetor. ";
  cin >> N;
  for (int i = 0; i < N; i++) {
    cout << "Valor " << i << ". ";
    cin >> aux;
    v[i] = aux;
  }
  maximoMinimo(v, N, &maximo, &minimo);
  cout << "Minimo: " << minimo;
  cout << "\nMÃ¡ximo: " << maximo;
}
