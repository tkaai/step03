# Блочная система

клачисечкая БС
размер = контент + внешний отступ (margin) + внешний отступ (pading) + рамка(border)
костыль!!! - зазор между блоками, если тэги НЕ идут вплотную друг за другом
кваждый блок пытается захватить "весь мир" по горизонтали

для чего нужен box-sizing: border-box;???
ответ - меняется правило вычесления размера блока... размер = [контент + внутренний отступ (pading) + рамка (border)] + внешний отступ (margin)
