* TODO [2015-01-03 Sat] perisubutil: remove caller()

  L<Perinci::Sub::Wrapper> will generate wrapper that modifies caller() for the
  wrapped subroutine (like in L<Hook::LexWrap>), so this module's caller() will
  not be needed in the future.
