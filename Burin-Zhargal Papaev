#include <cstdint>

// Функция для инвертирования выбранных битов в участке памяти
void invert_bits(uint8_t* memory, size_t length, uint8_t bit_mask) {
  // Проходим по каждому байту в участке памяти
  for (size_t i = 0; i < length; ++i) {
    // Инвертируем только те биты, которые установлены в маске
    memory[i] ^= bit_mask;
  }
}
