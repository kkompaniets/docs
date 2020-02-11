## orders.printReceipt: Распечатать пречек

```javascript
Poster.orders.printReceipt(1503219480866, 'loremipsum 123', 'Для сканирования QR кода используйте приложение Приват24')
```

Метод печатает чек, с опциональным QR кодом.

### Аргументы

Аргумент | Описание
-------- | --------
1-й, id | ID заказа (unix-timestamp в миллисекундах)
2-й, qrCode | Строка из которой будет сгенерирован QR код, опциональный параметр
3-й, qrCodeTitle | Заголовок который будет напечатан в низу QR кода, опциональный параметр