# psp-pandora-battery-for-arduino

Эмулятор сервисной батареи пандоры, написаный под ардуино. В качестве контроллера подойдёт Атмега 88/168/328. 
При включении на плате мигнёт светодиод 3 раза (это значит, что эмуляция работает в сервисном режиме ffffffffffffffff), если зажать нижнюю кнопку на плате, то при включении 
светодиод просто загорится (значит, что сейчас работает обычный режим батареии 1234568). Поддерживаются все материнские платы до ta-092. Начиная с ta-093 необходимо наличие 
дополнительных ответов, которые ещё не нашли.