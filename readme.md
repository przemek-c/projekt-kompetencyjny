Aby sprawdzić, czy strona HTML działa w GitHub Codespaces, wykonaj następujące kroki:

1. **Uruchomienie serwera HTTP:**
- Otwórz terminal w GitHub Codespaces.
 - Uruchom prosty serwer HTTP, np. za pomocą Python:
           ```sh
                python3 -m http.server 8000
                    ```
                        - Serwer uruchomi się na porcie 8000.

                        2. **Otwórz stronę w przeglądarce:**
                           - W GitHub Codespaces kliknij ikonę "Port Forwarding" (Przekierowanie portów) w panelu bocznym.
                              - Znajdź port 8000 i kliknij "Open in Browser" (Otwórz w przeglądarce).

                              3. **Sprawdź stronę:**
                                 - W przeglądarce otworzy się strona główna serwera HTTP.
                                    - Przejdź do pliku 

                                    main.html

                                    , dodając go do URL, np.:
                                         ```
                                              http://localhost:8000/main.html
                                                   ```
                                                      - Sprawdź, czy strona wyświetla się poprawnie.

                                                      Jeśli wszystko jest poprawnie skonfigurowane, powinieneś zobaczyć swoją stronę HTML w przeglądarce.   - Sprawdź, czy strona wyświetla się poprawnie.

                                                      Jeśli wszystko jest poprawnie skonfigurowane, powinieneś zobaczyć swoją stronę HTML w przeglądarce.