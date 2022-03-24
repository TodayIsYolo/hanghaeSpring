package com.spring.blog.domain;

import lombok.Getter;

@Getter
public class BlogRequestDto {
    private String username;
    private String title;
    private String contents;
}
