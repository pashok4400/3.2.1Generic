## Заметки

Исключили поля проекта с целью упрощения:

Для класса Note:

 *   val ownerId: Int,
 *   val viewUrl: String

Для класса Comment:

  *  val ownerId: Int,
  *  val attachments: Array,
  *  val sticker_id: UInt,
  *  val guid: int не используем

Возврат комментариев в класс Comment переменная var isDelete: Boolean = false.