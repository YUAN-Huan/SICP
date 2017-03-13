# SICP
3.1
(define (make-accumulator balance)
  (lambda (amount)
    (begin (set! balance (+ balance amount))
           balance)))
