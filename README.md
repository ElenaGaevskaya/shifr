# shifr
При запуске клиент и сервер генерируют каждый свою пару ключей. При подключении клиент посылает серверу свой открытый ключ. В ответ, сервер посылает клиенту открытый ключ сервера. Клиент посылает сообщение серверу, шифруя его своим закрытым ключом и открытым ключом сервера. Сервер принимает сообщение, расшифровывает его сначала своим закрытым ключом, а потом - открытым ключом клиента. Обратное сообщение посылается аналогично. Для Шифровки - расшифровки используем фукнции симметричного шифрования из предыдущей работы по симметричному шифрованию по Unix
143402901-b525f449-abb6-4a0f-bffd-fae3a80cc02d
